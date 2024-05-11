# Cansado de estudar feito robô? 🤖
## Apresentamos seu Chatbot Professor Particular Personalizado! 🎓

Imagine ter um professor dedicado, que se adapta ao SEU ritmo e te ajuda a dominar qualquer matéria! 🤩

Com este código inovador, você terá:

- Plano de Estudos Personalizado: Esqueça métodos genéricos! Você informa a matéria, o conteúdo e seu nível (avançado, intermediário ou básico) e boom! O Chatbot cria um plano sob medida, com links para livros, vídeos, exemplos práticos... tudo que você precisa para turbinar seu aprendizado 🚀.
- Quiz Interativo para testar seus conhecimentos: Nada de decorar fórmulas! O Chatbot formula perguntas desafiadoras de múltipla escolha, te mantendo engajado e pronto para qualquer prova 💪.
- Professor Virtual sempre à disposição: Se errar, ele te corrige e te coloca de volta no caminho. Acertou? Ele te parabeniza e te leva para o próximo nível! 🏆
Chega de métodos engessados e chatos! 🥱 Com este Chatbot, estudar se torna uma aventura interativa e personalizada.

### Diga adeus ao tédio e olá para o aprendizado eficiente! 🎉

Experimente agora! Digite seu nome, a matéria que deseja dominar e prepare-se para uma jornada de aprendizado incrível! 🧠

## Como usá-lo no seu [Google Colab](https://colab.new)?

- Acesse o Google Colar pelo link em azul acima.
- Instale o modelo generativo

`!pip install -q -U google-generativeai`

- Importe ele e entre com sua Google Key

`import google.generativeai as genai`
`GOOGLE_API_KEY="Substitua aqui pela sua chave"
genai.configure(api_key=GOOGLE_API_KEY)`

- Configure-o

`generation_config = {
    "candidate_count":1,
    "temperature": 0.5
}``

- Escolha o modelo que deseja usar 

`model = genai.GenerativeModel(model_name="gemini-1.0-pro",
                              generation_config=generation_config)`

### E agora é só colar o código do arquivo PROFESSOR PARTICULAR!
