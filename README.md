# Phishing para capturar credenciais em redes sociais fake

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```

![image](https://github.com/user-attachments/assets/7ed5dd19-f804-430d-adb5-bd4f0a300857)


- Tipo de ataque: ``` Social-Engineering Attacks ```
- digite a opção 1 e pressione Enter

![image](https://github.com/user-attachments/assets/f7f188e5-f75e-4a79-9b13-104e72e3223b)

  
- Vetor de ataque: ``` Web Site Attack Vectors ```
- digite a opção 2 e pressione Enter

![image](https://github.com/user-attachments/assets/e397c0bb-2767-42be-bc61-42881eb898a3)

  
- Método de ataque: ```Credential Harvester Attack Method ```
- digite a opção 3 e pressione Enter

![image](https://github.com/user-attachments/assets/3aee292e-c624-4cfc-83c4-4226216e1939)

- Método de ataque: ``` Site Cloner ```
- digite a opção 2 e pressione Enter

![image](https://github.com/user-attachments/assets/6dec5931-be0f-41dd-8c78-9c74022e0c22)

- Obtendo o endereço da máquina: ``` ifconfig ```
- pressione ENTER na para permanecer com o endereço IP indicado

![image](https://github.com/user-attachments/assets/69d217ef-d1c8-492f-b679-ebe69124533c)


- URL para clone: http://www.facebook.com
- agora digite o endereço da rede social e pressione ENTER no final
- em seguida já vai ser criado uma página fake para utilizarmos como phishing

![image](https://github.com/user-attachments/assets/919b3a99-704e-49d2-ae77-f368a7740be3)


### Realizando teste
- Agora em outro equipamento na mesma rede, abrir o navegador e entrar com o endereço IP da nossa página fake da rede social.
![image](https://github.com/user-attachments/assets/912dd390-769f-48cd-bec6-ef3dfb5c584f)

- No nosso servidor da página já mostra a saida de output informando que alguém acessou a página.
![image](https://github.com/user-attachments/assets/e87ab270-6af3-4dd9-ac69-37399cfc3beb)

- Entrar com as credenciais e pressionar ENTER

![image](https://github.com/user-attachments/assets/644bf203-659b-46bb-90ef-8ffbed373e28)

- Agora podemos visualizar a credencial capturado do usuário.

![image](https://github.com/user-attachments/assets/7008120a-4356-4358-8b3f-f74a1cf3ff3e)

Finalizamos nosso desafio phishing com sucesso.
