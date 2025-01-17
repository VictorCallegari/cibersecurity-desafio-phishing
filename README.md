# Phishing para Captura de Senhas do Instagram

## Ferramentas Necessárias
- **Kali Linux**
- **setoolkit**

## Configurando o Phishing no Kali Linux

### 1. Acesso Root
Para iniciar, torne-se root:
```bash
sudo su
```

### 2. Iniciando o SEToolkit
Execute o comando:
```bash
setoolkit
```

### 3. Selecionando o Tipo de Ataque
Escolha a opção correspondente:
1. **Social-Engineering Attacks**

### 4. Escolhendo o Vetor de Ataque
Escolha o vetor:
2. **Web Site Attack Vectors**

### 5. Método de Ataque
Selecione o método:
3. **Credential Harvester Attack Method**

### 6. Clonando o Site
Utilize a opção:
2. **Site Cloner**

### 7. Obtendo o Endereço da Máquina
Descubra o IP da máquina para hospedar o ataque:
```bash
ifconfig
```

### 8. Inserindo a URL para Clone
Digite o URL do site que deseja clonar. Neste caso, use o Instagram:
```
http://www.instagram.com
```

### 9. Resultado
![imagem do resultado](https://github.com/VictorCallegari/cibersecurity-desafio-phishing/blob/main/result.jpeg)

## Aviso Importante
Este material é fornecido apenas para **fins educacionais** e de **conscientização sobre segurança**. Qualquer uso inadequado ou mal-intencionado é estritamente proibido e pode violar leis locais e internacionais.
