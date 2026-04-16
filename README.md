# Monitoramento de Sistema

Projeto desenvolvido durante o curso **Linux: criando script de monitoramento de sistema** da Alura.

## 📌 Objetivo
Criar um script em shell para monitorar recursos do sistema (CPU, memória, disco) e configurar sua execução automática usando **systemd** com arquivos `.service` e `.timer`.

## ⚙️ Funcionalidades
- Verifica uso de CPU, memória e disco.
- Gera relatórios simples no terminal.
- Pode ser executado manualmente ou agendado com systemd.

## 🚀 Como usar
1. Clone este repositório:
   ```bash
   git clone https://github.com/taiones/Monitoramento-Sistema.git
   cd Monitoramento-Sistema
2. Dê permissão de execução ao script:
   ```bash
   chmod +x monitoramento_sistema.sh
4. Execute manualmente:
   ```bash
    ./monitoramento_sistema.sh
6. (Opcional) Instale os arquivos .service e .timer:
   ```bash
   sudo cp monitoramento_sistema.service /etc/systemd/system/
   sudo cp monitoramento_sistema.timer /etc/systemd/system/
   sudo systemctl daemon-reload
   sudo systemctl enable --now monitoramento_sistema.timer

## 🛠️ Tecnologias
Linux (bash)

systemd (services e timers)

## 📚 Aprendizado
Este projeto reforçou conceitos de:

Automação com shell script

Gerenciamento de processos e serviços no Linux

Uso de timers e unidades systemd

## 👤 Autor
**Taiones Costa**  
[LinkedIn](https://www.linkedin.com/in/taiones) | [GitHub](https://github.com/taiones)

