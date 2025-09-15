## Projeto - Órtese de Monitoramento da Região Lombar

Este repositório contém os arquivos referentes ao **Projeto 02** da disciplina de Órteses e Próteses.  
O projeto consiste no desenvolvimento de uma **órtese ativa para monitoramento da região lombar**, equipada com sensores e atuadores para correção postural em tempo real.

---

## Participantes 1 - na disciplina de órtese e prótese a parte bruta do projeto foi feita e ao final da disciplina foi desenvolvido um produto, o protótipo de uma órtese ativa para monitoramento de lombar, participaram da fase 1 do projeto:
-- Raylam Wendel da Silva
- Lucas de Sá Penaforte
- Nathalia Giovana Soares da Paz
- Pablo Henrico Farias da Costa  
- Orientadora: Luciana de Andrade Mendes
## Participantes 2 - o projeto que idealizei teve uma segunda parte que foi a confecção de uma PCB pra deixar o circuito mais compacto e próximo de um produto final, essa parte foi desenvolvida como projeto da disciplina "Técnicas de prototipação e montagem de circuitos e sistemas eletrônicos".
-- Raylam Wendel da Silva
- Ícaro Luiz de Souza Lino   
- Janilton Gomes de Farias  
- Orientador: Heitor Medeiros Florencio
---

## Motivação
A dor lombar afeta cerca de **65% da população mundial anualmente**, sendo considerada pela **OMS** como a principal causa de incapacidade no planeta.  
Nos últimos anos, os custos com tratamentos, perdas de produtividade e procedimentos cirúrgicos vêm aumentando de forma significativa, tornando-se um problema de saúde pública.

---

## Proposta do Projeto
Foi desenvolvida uma órtese ativa para monitoramento lombar, equipada com:

- **2x MPU-6050** – sensores inerciais para mapear a postura em tempo real  
- **1x ESP32** – microcontrolador principal  
- **1x Motor vibratório (VIBRACALL)** – feedback corretivo  
- Componentes auxiliares: resistores, transistor 2N2222, capacitor, diodo  

**Funcionamento:**  
Quando uma postura inadequada é mantida por um período predefinido, o sistema ativa o motor vibratório para promover a **conscientização e a reeducação postural**.

---

## Estrutura do Repositório
- **BOM_orteseAtv_Projeto02.csv** → Lista de materiais  
- **Gerber_orteseAtv_Gebers_Projeto02.zip** → Arquivos de fabricação da PCB  
- **Layout_orteseAtv_Projeto02.pdf** → Layout da placa em PDF  
- **Layout_Projeto02.png** → Imagem do layout da PCB  
- **PCB_PCB_orteseAtv_2025-01-27.json** → Arquivo fonte do projeto da PCB  
- **Peojeto02_Apresentacao.pdf** → Apresentação final do projeto  

---

## Resultados
- Protótipo de PCB desenvolvido e validado.  
- Simulação e testes indicam que o sistema consegue **detectar posturas inadequadas** e fornecer feedback corretivo imediato.  

---

## Referências
- Organização Mundial da Saúde (OMS) – Low back pain fact sheets  
- Casser, H.-R.; Seddigh, S.; Rauschmann, M. (2016). *Acute Lumbar Back Pain*  
- Bier­nath, A. (2024). Dor nas costas: orientações do 1º manual da OMS  
- [The Lancet – Global prevalence of low back pain](https://www.thelancet.com/)  

---

## 🚀 Próximos Passos
- Implementar versão embarcada da órtese com feedback via aplicativo.  
- Ampliar testes em diferentes perfis de usuários.  
- Otimizar o layout da PCB para prototipagem industrial.  
