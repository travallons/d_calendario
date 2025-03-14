# 📅 Tabela Calendário Completa para Bancos de Dados Brasileiro  

Este repositório disponibiliza uma **Tabela Calendário** altamente detalhada e otimizada para uso em **Power BI, SQL e outras ferramentas de análise de dados**. Ela inclui:  

✅ Datas de **1900 a 2100**  
✅ Formatos diversos (ISO, abreviações, PT-BR/EN-US)  
✅ Hierarquias de tempo: **dias, semanas, meses, bimestres, trimestres, semestres e etc.**  
✅ Identificação de **feriados nacionais e estaduais** e regras de dias úteis  
✅ Flags úteis: **primeiro/último dia do mês, do ano, ano bissexto**  

## 📂 Arquivos Disponíveis  

- **📄 `d_calendario.xlsb`** → Planilha Excel com todos os dados  
- **📜 `d_calendario.txt`** → Código M para Power Query (Power BI e Excel)
- **📜 `d_calendario_dinamico.txt`** → Código M para Power Query, data de início e fim baseado na sua fonte de dados (Power BI e Excel) 
- **📊 `Tabela Calendário Brasileiro Completa.pbix`** → Modelo pronto no [Power BI](https://app.powerbi.com/view?r=eyJrIjoiOWJmMjAzM2UtYTdkZi00ODFiLWI5MjItYzgwMGI0NGY2MWRjIiwidCI6IjVmNmZmN2JiLTQ2Y2QtNGM0Zi1hNjcwLTI1ZWNiMmI3OWJjZSJ9&embedImagePlaceholder=true&pageName=4efdc65808dee84ff498)

> **ℹ️ Importante:**  
> O arquivo Excel está no formato **`.xlsb` (Binary Workbook)**, que reduz o tamanho do arquivo e melhora o desempenho no Excel. No entanto, algumas ferramentas externas podem não suportá-lo nativamente. Caso precise de outro formato, você pode salvar como `.xlsx` ou `.csv` dentro do próprio Excel.

## 📌 Como Usar  

### 🟢 No Power BI  
1. **Excel**: Importe o `d_calendario.xlsb` pelo **Obter Dados > Excel**.  
2. **Power Query**: Copie e cole o código do `d_calendario.txt` no Editor Avançado do Power Query.  
3. **Power Query**: Copie e cole o código do `d_calendario_dinamico.txt` no Editor Avançado do Power Query para que seu calendário possua range baseado na sua fonte de dados.
4. **Modelo Pronto**: Abra o `Tabela Calendário Brasileiro Completa.pbix` e explore o modelo já configurado.  

### 🟣 No SQL Server  
1. Crie uma tabela no seu banco de dados.  
2. Importe os dados via Power BI, Excel ou scripts SQL.  

## 🎯 Objetivo  

Este projeto tem como objetivo facilitar a implementação de um **calendário completo e flexível**, reduzindo o tempo de preparação de dados e garantindo consistência nos cálculos temporais.  

## 🔗 Contribua!  

📢 Se você encontrou valor nesse material, **deixe uma estrela ⭐ no repositório** e compartilhe com a comunidade!  

🚀 Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/travallons/) para mais conteúdos sobre dados!  
