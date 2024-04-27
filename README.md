## Instalação do Kali Linux em uma Máquina Virtual usando VirtualBox

1. **Baixar e Instalar o VirtualBox:**
   - [Baixar o VirtualBox](https://www.virtualbox.org/wiki/Downloads)
   - Siga as instruções para instalação.

2. **Baixar a imagem do Kali Linux para o VirtualBox:**
   - [Baixar a imagem do Kali Linux](https://www.kali.org/downloads/)
   - Escolha a versão adequada para sua máquina e siga as instruções para download.
   - 
**ANNONSURF**

3. **Instalando e Configurando o Anonsurf:**
   - Abra um terminal e execute os seguintes comandos:
     ```bash
     mkdir Anonsurf && cd Anonsurf
     git clone https://github.com/Und3rf10w/kali-anonsurf.git
     sudo ./installer.sh
     sudo anonsurf
     ```

4. **Comandos úteis no Anonsurf:**
   - `anonsurf start`: Inicia o serviço.
   - `anonsurf stop`: Para o serviço.
   - `anonsurf restart`: Reinicia o serviço.
   - `anonsurf change`: Altera o IP do host.
   - `anonsurf myip`: Mostra o IP atual.
   - `anonsurf status`: Mostra o status do serviço em tempo real (upload e download).
   - 
**TOR**
5. **Instalando o Navegador Tor:**
   - Execute os seguintes comandos no terminal:
     ```bash
     sudo apt install -y tor torbrowser-launcher
     
      - `torbrowser-launcher` : Executar no terminal
     
     ```
   - Abra o navegador Tor e vá para as configurações.
   - Marque a opção "Use Bridge" e selecione uma "Built-in Bridge" (Obsfs4).

## Testando o Acesso à Dark Web
- Teste o link [http://tmnguwi25tpvx6lhsmmnxwqvkntepyqtaz3adhcezudl74ae7oclc7id.onion/](http://tmnguwi25tpvx6lhsmmnxwqvkntepyqtaz3adhcezudl74ae7oclc7id.onion/)
