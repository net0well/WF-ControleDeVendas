<h1>Sistema de Vendas - Windows Forms</h1>

<p>Este é um projeto de um <strong>Sistema de Vendas</strong> desenvolvido em <strong>C#</strong> com <strong>Windows Forms</strong> e <strong>MySQL</strong> como banco de dados. O sistema foi criado para gerenciar operações de vendas, funcionários, clientes e produtos. As queries SQL são <strong>hard coded</strong>, sem a utilização de nenhum ORM.</p>

<h2>Funcionalidades Principais</h2>
<ul>
    <li><strong>Tela de Login</strong>: Permite acesso seguro ao sistema, com autenticação de usuários.</li>
    <li><strong>Gestão de Funcionários</strong>: Sistema com níveis de acesso diferenciados (Gerente e Funcionários).</li>
    <li><strong>Cadastro de Clientes</strong>: Tela para gerenciamento completo dos clientes.</li>
    <li><strong>Cadastro de Produtos</strong>: Registro e atualização de produtos disponíveis para venda.</li>
    <li><strong>Tela de Vendas</strong>: Funcionalidade completa para processar vendas.</li>
    <li><strong>Histórico de Vendas</strong>: Visualização de todas as vendas realizadas, com filtro por período.</li>
    <li><strong>Tela de Pagamento</strong>: Interface básica para processar pagamentos.</li>
</ul>

<h2>Tecnologias Utilizadas</h2>
<ul>
    <li><strong>C#</strong> com <strong>Windows Forms</strong> para o desenvolvimento da interface do usuário.</li>
    <li><strong>MySQL</strong> para o banco de dados, com queries escritas diretamente no código (sem ORM).</li>
</ul>

<h2>Como Executar o Projeto</h2>
<ol>
    <li>Clone este repositório para o seu ambiente local:
        <pre><code>git clone https://github.com/seuusuario/sistema-de-vendas.git</code></pre>
    </li>
    <li>Configure o banco de dados MySQL:
        <ul>
            <li>Crie o banco de dados e as tabelas necessárias utilizando o script SQL disponível em <code>/database/initial_setup.sql</code>.</li>
            <li>Ajuste a string de conexão no arquivo de configuração <code>App.config</code> com as suas credenciais do MySQL.</li>
        </ul>
    </li>
    <li>Compile e execute o projeto a partir da IDE (Visual Studio).</li>
</ol>

<h2>Estrutura do Projeto</h2>
<ul>
    <li><strong>Login</strong>: Validação de usuários para acessar o sistema.</li>
    <li><strong>Funcionários</strong>: Gerenciamento de funcionários com controle de níveis de acesso.</li>
    <li><strong>Clientes</strong>: Cadastro e edição de informações de clientes.</li>
    <li><strong>Produtos</strong>: Gestão do estoque e informações dos produtos.</li>
    <li><strong>Vendas</strong>: Realização de vendas e emissão de comprovantes.</li>
    <li><strong>Histórico de Vendas</strong>: Exibição das vendas com possibilidade de filtro por data.</li>
    <li><strong>Pagamentos</strong>: Processamento de pagamentos de maneira simples e funcional.</li>
</ul>

<h2>Próximos Passos</h2>
<ul>
    <li>Adicionar novas formas de pagamento.</li>
    <li>Implementar um módulo de relatórios avançados.</li>
    <li>Melhorar a interface do usuário com novos componentes.</li>
</ul>

<h2>Contribuições</h2>
<p>Sinta-se à vontade para contribuir com melhorias no projeto. Basta abrir um <strong>Pull Request</strong> com as suas sugestões.</p>

<h2>Licença</h2>
<p>Este projeto está licenciado sob a <a href="LICENSE">MIT License</a>.</p>
