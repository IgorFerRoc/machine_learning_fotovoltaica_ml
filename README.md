# ☀️ Previsão de Radiação Solar para Geração Fotovoltaica usando Machine Learning

Projeto desenvolvido para a disciplina de **Machine Learning Aplicado à Engenharia** (UFSJ), focado no processamento de dados climáticos do INMET e na modelagem preditiva de radiação solar. O objetivo é mapear o comportamento dinâmico do recurso solar utilizando arquiteturas de aprendizado de máquina para otimizar o dimensionamento e operação de sistemas fotovoltaicos.

## 👥 Integrantes do Grupo
* André Reis Rodrigues Filho
* Igor Ferreira Rocha
* Yuri Lopes Gomes de Paulo

---

## 📂 Estrutura do Repositório

**⚠️ OBSERVAÇÃO SOBRE OS DADOS:** As séries históricas originais do INMET utilizadas para o treinamento não foram incluídas neste repositório por excederem o limite de armazenamento do GitHub. No entanto, o arquivo de instruções na pasta `docs/` detalha o procedimento exato para baixá-los e organizá-los corretamente antes de executar os códigos.

| Diretório / Arquivo | Descrição |
| :--- | :--- |
| `📁 apresentacao/` | Contém o arquivo **`Testes.pdf`** com os slides/relatório detalhando a metodologia, testes e resultados preditivos. |
| `📁 dados/` | Pasta local destinada aos datasets brutos e tratados (vazia no repositório remoto por limitações de espaço). |
| `📁 docs/` | Contém o guia **`Passo a passo para baixar os dados (interesse no projeto 2021 a 2025).txt`**. |
| `📁 notebooks/` | Contém o **`Trabalho 2 Machine Learning - Fotovoltaico.ipynb`**, o Jupyter Notebook principal com o pipeline completo (Saneamento, Feature Engineering, modelos NARX, HistGradientBoosting e Ridge pós Lasso). |
| `📄 environment.yml` | Arquivo de exportação com as configurações e dependências exatas do ambiente virtual (Conda/Anaconda) para reprodução do projeto. |

---

## 🚀 Como reproduzir este projeto

Para garantir que não haja conflitos de versão (especialmente com a biblioteca Pandas restrita à versão 2.3.3 e os pacotes do SysIdentPy), recomendamos a utilização do gerenciador de ambientes Conda.

**1. Clone o repositório:**
```bash
git clone [https://github.com/IgorFerRoc/machine_learning_fotovoltaica.git](https://github.com/IgorFerRoc/machine_learning_fotovoltaica.git)
cd machine_learning_fotovoltaica
