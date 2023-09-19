# Cardápio Conectado

## Descrição

    O **Cardápio Conectado** é uma inovadora aplicação web de cardápio digital projetada para simplificar a experiência de restaurantes e clientes. Com nosso sistema intuitivo e altamente personalizável, os restaurantes podem criar e gerenciar facilmente seus menus online, enquanto os clientes desfrutam de uma maneira conveniente de explorar opções de alimentos, fazer pedidos e fornecer feedback valioso.

    ## Principais Recursos:

    - **Cardápio Digital Interativo:** Converta seu cardápio tradicional em uma versão digital e atraente, com imagens de alta qualidade, descrições detalhadas e preços atualizados em tempo real.

    - **Pedidos Online Simplificados:** Permita que os clientes naveguem pelo cardápio, façam pedidos e personalizem suas seleções de forma rápida e fácil.

    - **Múltiplas Opções de Pagamento:** Aceite pagamentos online seguros, incluindo cartões de crédito, carteiras digitais e muito mais.

    - **Gestão de Pedidos Eficiente:** Simplifique o gerenciamento de pedidos em tempo real, rastreando o status dos pedidos e atualizando automaticamente os tempos de preparação.

    - **Feedback e Avaliação:** Colete feedback dos clientes e avaliações de alimentos para melhorar constantemente a qualidade do serviço e dos produtos.

    - **Personalização Avançada:** Adapte a aparência do cardápio digital para refletir a identidade da sua marca e destaque pratos especiais e promoções.

    - **Administração Centralizada:** Gerencie todos os aspectos do seu cardápio e operações de restaurante a partir de um painel centralizado.

    O **Cardápio Conectado** é a solução perfeita para restaurantes que desejam aprimorar a experiência do cliente, aumentar a eficiência operacional e manter-se atualizados com as tendências tecnológicas em constante evolução. Facilitamos a transição para um ambiente digital, proporcionando um serviço excepcional e mantendo a satisfação do cliente em primeiro plano.

    Junte-se a nós nesta jornada e transforme a forma como o seu restaurante serve os clientes e cresce nos negócios.



## Capturas de Tela


## Instalação

    ```bash
    git clone https://github.com/Ferreira-S-I/multicc.git
    ```

    Rode os comandos:

    ```bash
    cd multicc
    cp .env.example .env
    composer install
    ```

    Laravel sail:

    ```bash
    sail up -d
    ```

    Rode os comandos:

    ```bash
    sail artisan key:generate
    sail artisan migrate
    sail npm i
    sail npm run dev
    ```

## Uso


    Create a new user account with the following command:

    ```bash
    sail artisan make:filament-user
    ```

    Open /admin in your web browser, sign in, and start your app!


