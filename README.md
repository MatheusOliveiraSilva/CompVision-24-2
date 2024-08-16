# PoseLandmarker

## Descrição

Este projeto utiliza o **PoseLandmarker** para detectar e reconhecer poses humanas em tempo real usando a câmera do iPhone. Antes de iniciar, certifique-se de que você tem o **CocoaPods** instalado em seu sistema, pois ele é usado para gerenciar as dependências do projeto.

!!!Atenção usuários de Windows, todo o repositório foi feito em um macboook air, e não tive a menor preocupação de fazer funcionar para um windows, boa sorte!!!

## Pré-requisitos

1. **Xcode**: Certifique-se de que o Xcode esteja instalado e atualizado. [Download do Xcode](https://developer.apple.com/xcode/).
2. **CocoaPods**: Ferramenta de gerenciamento de dependências para projetos Swift e Objective-C.

## Instalação do CocoaPods

Se você ainda não tem o CocoaPods instalado, siga os passos abaixo:

### 1. Instale o CocoaPods

Abra o Terminal e execute o comando:

```bash
sudo gem install cocoapods
```

 Depois da instalação verifique se a versão está correta com:

 ```bash
pod --version
```

### 2. Rode o Podfile para poder gerar a pasta Pods e atualizar o .xcworkspace:

Ainda no terminal execute:

 ```bash
git clone https://github.com/MatheusOliveiraSilva/CompVision-24-2.git
```

E depois:

 ```bash
cd seu-repositorio
pod install
```

Vai ser gerada a pasta Pods e o workspace, confirme que você tenha o Xcode instalado, se sim, só executar o comando:

 ```bash
open PoseLandmarker.xcworkspace
```

Se divirta!
Contato: matheusolivsilv.ai@gmail.com



