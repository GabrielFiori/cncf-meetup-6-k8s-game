## Repositório utilizado para o Meetup #06 do Cloud Native Araraquara-SP

Assista: https://www.youtube.com/watch?v=nrflAZreou0

## 🚀 Como subir sua infraestrutura e rodar o jogo

Siga os passos abaixo para criar sua infraestrutura na DigitalOcean e publicar seu próprio jogo:

1. **Crie sua conta na DigitalOcean**  
   Use o link: https://m.do.co/c/a5371331c01f

2. **Coloque os dados do cartão de crédito para conseguir o free trial na DigitalOcean**  
   Circulo na direita superior, clique em My Account e após entrar clique em "Add Payment Method".
   Após isso é importante que apareça "Free Trial Active"

4. **Gere seu Token de API**  
   No painel esquerdo da DigitalOcean, acesse **API** → **Generate New Token** e crie um token com Full Access.

5. **Faça um fork desse repositório** 

6. **Adicione o token nas secrets do GitHub**  
   No seu repositório, acesse:  
   **Settings** → **Secrets and Variables** → **Actions** → **New repository secret**

7. **Crie a secret `DO_TOKEN`**  
   - **Name:** `DO_TOKEN`  
   - **Secret:** cole o token gerado no passo 2.

8. **Execute o workflow de infraestrutura**  
   Vá até **Actions**, habilite os workflows e vá até **Create Infrastructure** e clique em **Run workflow** e após em **Run workflow** novamente.

9. **Aguarde o término da pipeline**  
   Assim que finalizar, acesse seu jogo pelo link:  
   ```
   https://suaconta.k8sgame.win
   ```
   > **Obs:** *suaconta* é o seu nome de usuário do GitHub minusculo.

Pronto! Sua infraestrutura estará criada automaticamente e seu jogo já estará no ar. 🎮🔥
