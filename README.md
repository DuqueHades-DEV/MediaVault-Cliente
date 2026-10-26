MediaVault Premium

O MediaVault é uma ferramenta avançada de captura de mídias (imagens e vídeos) desenvolvida para máxima performance, estabilidade e segurança. Com uma interface de terminal moderna (CLI), ele realiza o download e a filtragem automática de arquivos de forma inteligente.

Recursos:

- Captura de imagens e vídeos em alta qualidade.
- Filtro inteligente: remove logos, banners e thumbnails indesejadas automaticamente.
- Otimização de downloads: evita arquivos duplicados e versões menores da mesma mídia.
- Sistema de licença seguro: trava o uso em apenas 1 dispositivo por Key.
- Interface visual Premium com feedback de progresso em tempo real.

Requisitos:

Para rodar o MediaVault, você precisa de:
- Termux (Android) instalado. Baixe pela F-Droid para melhor compatibilidade.
- Python 3.10 ou superior.
- Conexão com a internet.

Instalação Rápida (Termux):

Abra o Termux e cole os comandos abaixo, um por um.

1. Instalar as dependências do sistema:
pkg update -y && pkg install git python -y

2. Clonar o repositório:
git clone https://github.com/DuqueHades-DEV/MediaVault-Cliente.git

3. Entrar na pasta do projeto:
cd MediaVault-Cliente

4. Instalar as bibliotecas do Python:
pip install requests beautifulsoup4 cryptography

Como Usar:

Ainda dentro da pasta do projeto no Termux, execute:
python MediaVault.py

O sistema abrirá o painel no terminal. Cole a sua Key de Acesso quando solicitado. Após a validação, basta colar o link da página que deseja capturar as mídias.

Aviso Legal:

Esta ferramenta é destinada apenas para uso pessoal e educacional. Os desenvolvedores não se responsabilizam pelo uso indevido do software ou violação de direitos autorais.

Desenvolvido por DuqueHades-DEV
