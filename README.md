## Desafio de projeto da DIO [Criação de um Phishing com o Kali Linux](https://web.dio.me/lab/criando-um-phishing-no-kali-linux/learning/e750f6d3-285c-4920-bd78-24d4ce1e515c?back=/play)

---

# Phishing para captura de senhas do Facebook

## Ferramentas
* [Kali Linux](https://www.kali.org/get-kali/#kali-platforms)
* setoolkit

## Configurando o Phishing no Kali Linux
* Acesso root: sudo su  
* Iniciando o setoolkit: setoolkit
  * Caso o comando não funcione clone o repositório da ferramenta:
  ```bash
  sudo git clone https://github.com/trustedsec/social-engineer-too
  ```
  * Após clonar o repositório, entre na pasta do projeto:
    ```bash
    cd social-engineer-toolkit
    ```
  * Agora, ao invés de apenas setoolkit, tente rodar diretamente o script:
    ```bash
    sudo python3 setoolkit
    ```
* Tipo de ataque: Social-Engineering Attacks
  * ![img1](https://github.com/JoelPB/Phishing_Kali_DIO/blob/master/img/1img.png)  
* Vetor de ataque: Web Site Attack Vectors
  * ![img2](https://github.com/JoelPB/Phishing_Kali_DIO/blob/master/img/2img.png)
* Método de ataque: Credential Harvester Attack Method
  * ![img3](https://github.com/JoelPB/Phishing_Kali_DIO/blob/master/img/3img.png)
* Método de ataque: Site Cloner
  * ![img4](https://github.com/JoelPB/Phishing_Kali_DIO/blob/master/img/4img.png)
 
* Obtendo o endereço da máquina: ip a
  * Basta clicar enter para utilizar o seu IP
    
* URL para clone: https://www.facebook.com
  * ![img5](https://github.com/JoelPB/Phishing_Kali_DIO/blob/master/img/5img.png)

## Resutados
![img6](https://github.com/JoelPB/Phishing_Kali_DIO/blob/master/img/6img.png)


### OBS.:
Como vemos o método não funciona nos navegadores atuais, assim que fizer em um navegador desatualizado postarei o resultado.
