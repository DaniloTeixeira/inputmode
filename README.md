- Inputmode
    - “inputmode” é um **atributo global que sugere o tipo de dado que será inserido pelo usuário no elemento selecionado, ele exibirá um teclado virtual adequado ao valor do atributo em telas que usam teclado virtual, e isso contribuirá para a melhora na UX.*
    
    ***EXEMPLO: <input type=”text” inputmode=”tel” />***
    
    O inputmode pode ter anguns valores, vamos vê-los abaixo:
    
    - none → Não exibe nenhum teclado
    - text → Teclado padrão para a localidade do usuário
    - decimal → Teclado numérico com separador de dígitos e decmimal (. ou ,). Pode ou não exibir o sinal de menos
    - numeric → Teclado numérico, apenas com os números de 0 a 9. Pode ou não exibir o sinal de menos
    - tel →  Teclado numérico, incluindo de 0 a 9, asterísco(**) e cerquilho(#*). Esse tipo requer que o input use o type=”tel”>
    - search → Teclado otimizado para busca, o botão de submit será um ícone de busca.
        
        OBS: Em sistemas Android, exibe um ícone de “Enter” como botão. Em sistemas IOS, exibe o botão “Go”
        
    - email → Telcado otimizado para inserir endereço de e-mail, inclui o caractere arroba(@), o ponto(.) e o domínio .com ou .com.br será exibido de acordo com a localidade do usuário.
    - url → Teclado otimizado para uso de URLs. Pode ou não exibir a barra(/), pode exibir o histórico de acesso. Esse tipo requer que o input use o type=”url”
    
    * *Atributo que pode ser utilizado em qualquer tag HTML, porém pode não ter nenhum efeito em algumas delas.*