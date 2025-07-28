Sistema de Botão de Pânico - IFPB

Este repositório contém o código-fonte e a documentação do Sistema de Botão de Pânico, um projeto acadêmico desenvolvido por Alexandre Freitas de Lima Pacheco e Robson Luan Fernandes Pereira como requisito para a disciplina de Padrões de Projetos do curso de Engenharia de Computação do IFPB - Câmpus Campina Grande.

🚀 Demonstração ao Vivo

Acesse a aplicação em funcionamento através do link abaixo:
https://alexandre-pacheco.github.io/Sistema-de-Bot-o-de-P-nico-IFPB/

✨ Visão Geral da Aplicação

<img width="863" height="534" alt="Opera Instantâneo_2025-07-28_160038_gemini google com" src="https://github.com/user-attachments/assets/e6d13706-cb54-4bf1-9d1e-17a0a0c05965" />



<img width="1078" height="688" alt="Opera Instantâneo_2025-07-28_160115_gemini google com" src="https://github.com/user-attachments/assets/1ae771d5-9bff-4d67-8908-ae4be0a5cc09" />



<img width="1088" height="822" alt="Opera Instantâneo_2025-07-28_160133_gemini google com" src="https://github.com/user-attachments/assets/2a011ffe-6836-4ee9-b43f-2c6d5c1d5fcc" />



<img width="1088" height="883" alt="Opera Instantâneo_2025-07-28_160213_gemini google com" src="https://github.com/user-attachments/assets/688e9463-36ae-402c-9391-5e9caaf159d1" />



<img width="1143" height="955" alt="Opera Instantâneo_2025-07-28_160328_gemini google com" src="https://github.com/user-attachments/assets/c845c616-b1bf-4488-b3b0-fde2a0eed686" />


🎯 Sobre o Projeto

O Sistema de Botão de Pânico é uma solução web projetada para aumentar a segurança da comunidade acadêmica (alunos, professores e técnicos) dentro das instalações do campus. Ele oferece um meio rápido e eficaz de solicitar ajuda em situações de emergência, enviando um alerta geolocalizado em tempo real para uma central de monitoramento administrada pela equipe de segurança.

📋 Funcionalidades Principais

•	Dois Perfis de Acesso:

o	Área do Usuário: Interface limpa para alunos e professores acionarem o botão de pânico.

o	Área do Administrador: Painel protegido por login para a equipe de segurança gerenciar alertas e usuários.

•	Acionamento Seguro: O botão de pânico requer que o usuário pressione por 3 segundos para evitar disparos acidentais.

•	Central de Monitoramento: Visualização de alertas ativos em tempo real, com informações do usuário e localização.

•	Gestão de Incidentes: A equipe de segurança pode gerenciar todo o ciclo de vida de um alerta (Pendente → Em Atendimento → Resolvido/Falso Alarme).

•	Cadastro e Gestão de Usuários: Administradores podem cadastrar e excluir usuários (alunos/professores) do sistema.

•	Geração de Relatórios: Ferramenta para criar relatórios estatísticos sobre os incidentes ocorridos.

🛠️ Arquitetura e Padrões de Projeto

Este projeto foi construído como uma aplicação de página única (SPA) utilizando HTML5, Tailwind CSS e JavaScript puro. A arquitetura foi pensada para ser modular, resiliente e de fácil manutenção, aplicando 9 padrões de projeto fundamentais para resolver desafios específicos:

<img width="621" height="807" alt="Opera Instantâneo_2025-07-28_204421_docs google com" src="https://github.com/user-attachments/assets/7a7df342-5de0-4150-8675-78b28284944d" />



📂 Estrutura do Código

Para facilitar a demonstração e o compartilhamento, toda a aplicação está contida em um único arquivo index.html. Dentro dele, a estrutura está organizada da seguinte forma:

1.	 Importação de fontes e do Tailwind CSS, além de estilos básicos.

2.	 Estrutura HTML de todas as telas (Seleção de Perfil, Usuário, Login de Admin, Painel de Admin).

3.	 Todo o código JavaScript, separado em seções claras:

o	Gerenciamento de Views (telas).

o	Dados Globais e Função de Log.

o	Implementação de cada um dos 9 Padrões de Projeto, com comentários explicativos.

o	Lógica da Interface do Usuário (UI) e associação de eventos.


👨‍💻 Autores

•	Alexandre Freitas de Lima Pacheco

•	Robson Luan Fernandes Pereira

📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
