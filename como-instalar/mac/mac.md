# Instalando o Git

Existem várias maneiras de instalar o Git em um Mac, como através do **XCode** e também do próprio **Homebrew**.

### **Xcode**

O mais fácil é provavelmente instalar as ferramentas de linha de comando Xcode. Você pode fazer isso simplesmente rodando **`git`** a partir do **Terminal** pela primeira vez. Se você não tiver o Git instalado, ele irá pedir para instalá-lo.

### **Homebrew**

Instale o [homebrew](https://brew.sh/) utilizando o comando abaixo:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

E em seguida rode o seguinte comando:

```bash
brew install git
```

## Configurações iniciais do Git

Para verificar se o Git foi instalado corretamente você pode rodar o comando no terminal:

```bash
git --version
```

Se retornar a versão do Git é porque foi instalado corretamente.

Em seguida você pode configurar o usuário e e-mail usando os comandos abaixo.

```bash
git config --global user.name "Seu Nome"
```

e em seguida

```bash
git config --global user.email "seu e-mail"
```

Você deve substituir seu `Seu Nome` pelo seu nome e `seu e-mail` pelo seu e-mail do Github