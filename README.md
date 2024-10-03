# *ConstrantLayout*
Esse código representa a implementação de uma tela de login para um aplicativo Android, utilizando Java e XML. Aqui está um resumo dos principais componentes e da estrutura:

# *Resumo do Código Java ( MainActivity.java)*
Classe Principal : MainActivityé uma subclasse de AppCompatActivity, que é base para a criação de atividades no Android.

Método onCreate : Este método é chamado quando a atividade é criada. Ele chama o método da superclasse e define o layout da atividade como activity_main.

# *Resumo do Layout XML ( activity_main.xml)*
Estrutura Principal : O layout é construído com um ConstraintLayout, que permite o posicionamento flexível e responsivo dos elementos na tela.

# Elementos do Layout :
TextView ( title) : Exibe o título "Livraria Capítulo Final" na parte superior da tela, com uma formatação de texto em negrito e uma cor específica.

EditarTextos :
username_edit_text: Campo para o usuário insira o nome de usuário, com fundo personalizado e um texto de dica ("Nome de usuário").
password_edit_text: Campo para o usuário inserir a senha, configurada para ocultar o texto, com um texto de dica (“Senha”).

Botão ( button2) : Um botão centralizado que permite ao usuário fazer login, rotulado como "Login".

TextViews Adicionais :
textView3: Texto que informa "Esqueceu sua senha?", provavelmente uma opção para recuperação de senha.
textView4: Um aviso simples que diz "Fale Conosco", que pode ser utilizado para informações de contato, embora não esteja vinculado a nenhuma funcionalidade no código apresentado.

![Captura de tela 2024-10-03 140255](https://github.com/user-attachments/assets/b34d4ca9-3669-4315-950f-0cbecd3cc26f)
