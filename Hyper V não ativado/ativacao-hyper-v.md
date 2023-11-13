Ao tentar utilizar o Docker no Windows, é essencial que o Hyper-V esteja devidamente ativado. Caso contrário, podem surgir erros durante a execução do Docker ou falta de recursos essenciais de virtualização. Abaixo estão as instruções para resolver o problema de Hyper-V não ativado no Windows.

## Instruções de Ativação do Hyper-V

1. **Ativação no BIOS:**
   - Reinicie o computador e acesse a BIOS.
   - Procure por opções relacionadas à virtualização (como "Intel Virtualization Technology (VT)" ou "AMD Virtualization (AMD-V)").
   - Ative a opção de virtualização, salve as configurações e saia da BIOS.

2. **Ativação no Painel de Controle do Windows:**
   - Abra o "Painel de Controle" e navegue para "Programas e Recursos > Ativar ou Desativar Recursos do Windows".
   - Marque as seguintes opções:
     - Hyper-V
     - Plataforma de Máquina Virtual
     - Plataforma do Hypervisor do Windows
     - Subsistema do Windows para Linux
   - Clique em "OK" e aguarde a instalação dos recursos.
  
    ![ativar e desativas 3](https://github.com/f5-nascimento/docker-installation-problems/assets/28812188/4c70318c-bfa2-44f9-9696-f8154e3d432a)


3. **Verificação da Ativação:**
   - Após a conclusão das etapas anteriores, verifique se o Hyper-V está ativado corretamente.
   - Abra o "Gerenciador Hyper-V" para confirmar a ativação.

Ao seguir essas instruções, você resolverá o problema de Hyper-V não ativado no Windows, permitindo o uso adequado do Docker.

