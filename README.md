#Projeto de Teste para Desenvolvedores

Vamos reproduzir uma landing page que fizemos para um cliente. 
Os materiais de apoios estão na pasta `/arquivos`.

##Algumas considerações:

- Utilizar PHP, HTML, CSS, JS;
- Utilizar Bootstrap (v3 ou v4);
- Pode-se utilizar: Gulp, SASS, NPM;
- A implementação deve ser responsiva;
- Testar em todos os principais navegadores (Google Chrome, Firefox);
- Tanto o carro quanto o conteúdo presente na seção azul claro são mudados ao se clicar na aba que contem o nome do carro;
- Criar um banco de dados para armazenar as informações que forem submetidas no formulário;
- Validar as informações submetidas para evitar que dados indevidos sejam enviados;
    * Nome: é obrigatório;
    * E-mail: é obrigatório, deve ser de um formato de e-mail válido (usar regex);
    * Telefone: é obrigatório, deve ser de um formato de telefone válido, aceitar DDD, aceitar tanto telefone fixo (formato: (99) 9999 9999) quando * telefone celular (formato: (99) 99999 9999);
    * Mensagem: é obrigatório, deve ter pelo menos 10 caracteres;
- Após ter os dados validados, armazenar os dados coletados no banco de dados;
- Manter código modularizado;