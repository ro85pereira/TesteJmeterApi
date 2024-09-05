Olá amigo, estou estudando sobre Api Rest e agora foi a vez de medir a performance do exemplo utilizado com a ferramenta Jmeter.
Estou seguindo os ensimamentos do projessor Julio Limas https://www.youtube.com/playlist?list=PLf8x7B3nFTl17WeEVj405tHlstiq1kNBX

A api utilizada é do professor montanha https://github.com/AntonioMontanha/gerenciador-viagens

Primeiramente deixei a Api funcionando localmente no Intellij

![API](https://github.com/user-attachments/assets/2427e475-10b4-4aa2-947a-51d21e4402b7)

Agora estudei os controlers no Swagger para assim preencher corretamente as requisições no Jmeter.

![Swagger](https://github.com/user-attachments/assets/bbecdaa1-4c8b-4e9e-8b34-705fa1645ef7)

No Jmeter realizo as configurações das requisições, como capturar um token e como cadastrar uma viagem para medir a performance.


![JmeterApi](https://github.com/user-attachments/assets/40ae440f-a6b6-474a-80fb-3a1ad35c958e)

Estes foram os resultados.

![JmeterApi3](https://github.com/user-attachments/assets/20e3bc3b-f818-4a9d-8478-cfe31b69a56a)
![JmeterApi2](https://github.com/user-attachments/assets/76ba8bb6-7bb1-4769-95a3-9929322646af)

Achei muito interessante a explicação do professor sobre a linha dos 90 e como ler os resultados dos testes utilizando uma média dos resultados pode induzir a erros de interpretação.
É sensacional como a linha dos 90 ordena os valores de forma crescente e e considera a "linha dos 90" dando uma interpretação totalmente diferente que considerar uma média dos resultados.

Também há um video com toda execução.
