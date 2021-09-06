# Teste de software

- Mostrar a presença de defeitos, e não a sua ausencia;  
- Testes exaustivos são impossíveis;  
- O teste inicial economiza tempo e dinheiro;  
- Cuidado com o paradoxo do inseticida;  
- Depende do contexto;  
- Ausencia de erros é uma ilusão.

**O custo de um bug na fase de entrega do software pode chegar a 100x o seu valor original**

### Tipos de testes:
- Funcionalidade;  
- Usabilidade;  
- Performance;  
- Segurança.

### Niveis de testes:
- Unidade;  
- Integração;  
- Sistema;  
- Aceitação.

### Tecnicas de testes:
- Funcional (Black-Box);  
- Estrutural (White-Box).

## Processo de um teste:
- Planejar => Projetar => Executar => Entregar => Planejar => Projetar ....

### Planejar:
- Leitura dos requisitos => Levantamento das duvidas => Ideias de testes => Estimativa
- Técnicas: Particão por equivalencia, Analise do valor limite, Tabela de decisão, testes por transição de estado.

### Projetar:
- Nome/Titulo => Objetivo => Pré-condições => Passo a passo => Resultado esperado

### Executar:
- Ambiente está atualizado? => Tenho os acessos necessarios? => Preciso de alguma massa de teste?
- Evidencias de erro: Print, Descrição do passo-a-passo de como chegar ao problema, descrição do erro, Navegador e sistema operacional utilizado, versão do sistema.
- Evidencias de sucesso: Print, Nome ou id do caso de teste, data de execução e versao do sistema, ciclo do teste.

### Entrega:
- Documentação, Status report, Evidencias de testes.

## Visao geral de teste:
### Plano de teste:
- **Casos de teste**;  
- **Ciclos de teste**;  

### Ciclos de teste:
- Versão do software;  
- Ambiente de teste;
- **Casos de teste**.

### Casos de teste:
- Massa de dados;  
- Passos de execução;  
- Resultado esperado.


## Testes estaticos
- Feitos antes de rodar o software

## Quando parar te testar?
- Tempo insuficiente;  
- Orçamento curto;  
- Falta de capacitação de identificar o erro;  
- Falta de capacitação de de executar ao menos um teste unitario.