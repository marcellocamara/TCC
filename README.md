PRODEC
======
PROGRAMA DE REGISTRO DE OCORRÊNCIAS EM DEFESA CIVIL

Este trabalho tem como propósito o desenvolvimento do sistema [PRODEC](http://www.prodec.defesacivil.rj.gov.br/) para versão mobile.

## Análise e teste

Um exemplar do aplicativo encontra-se disponível [clicando aqui](https://raw.githubusercontent.com/marcellocamara/TCC/master/APK/PRODEC.apk).

Um acesso está disponível para avaliação de terceiros:
```
email:  usuario@email.com
senha:  123456
```

## Sobre

O aplicativo foi desenvolvido para a plataforma Android, utilizando a linguagem de programação `Java` e o ambiente de desenvolvimento integrado (IDE) [Android Studio](https://developer.android.com/studio/?hl=pt-br) .

O design do aplicativo segue as diretrizes do [Material Design](https://material.io/design) e foi desenvolvido baseando-se no layout web (garantindo familiaridade para o usuário).

Para a comunicação com o banco de dados, foi desenvolvida uma `API`, utilizando a biblioteca [Volley](https://github.com/google/volley) para fazer as requisições de arquivos *`.php`* hospedados em um website de hospedagem gratuita, o [WebHost](https://www.000webhost.com/), que permite administração do banco de dados `MySQL`, através do `PhpMyAdmin`.

`Obs.1 : Como o serviço é gratuito, pode ser que as vezes apresente lentidão ou fique sem conexão.`

## Ferramentas / documentações utilizadas

- [CardView](https://developer.android.com/guide/topics/ui/layout/cardview)
- [GmailBackground](https://github.com/luongvo/GmailBackground)
- [JustifiedTextView](https://github.com/ufo22940268/android-justifiedtextview)
- [Material Design](https://material.io/design/)
- [RecyclerView](https://developer.android.com/guide/topics/ui/layout/recyclerview)
- [SmartTabLayout](https://github.com/ogaclejapan/SmartTabLayout)
- [StateProgressBar](https://github.com/kofigyan/StateProgressBar)
- [Toasty](https://github.com/GrenderG/Toasty)
- [Volley](https://github.com/google/volley)

## Imagens das telas

O aplicativo desenvolvido conta com suporte para rotação da orientação da tela, garantindo a integridade da interface em diferentes tamanhos e resoluções de tela.

A tabela abaixo mostra um comparativo entre as telas do aplicativo e do website (similaridade).

`Obs.2 : O Boletim de Ocorrência foi dividido em 4 telas.`

`Obs.3 : Na tela do Sistema, é possível navegar até a tela de Documentos clicando nas circunferências em verde, amarelo e vermelho.`

Tela | Aplicativo | Website
:---  | :---:  | :---:
SplashScreen | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Aplicativo/0.png) | -
Home | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Aplicativo/1.png) | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Site/1.png)
Cadastro de Adesão | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Aplicativo/2.png) | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Site/2.png)
Login | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Aplicativo/3.png) | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Site/3.png)
Fale Conosco | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Aplicativo/4.png) | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Site/4.png)
Sistema | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Aplicativo/6.png) | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Site/6.png)
Iniciar Boletim de Ocorrência | [1](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Aplicativo/7.png) - [2](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Aplicativo/8.png) - [3](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Aplicativo/9.png) - [4](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Aplicativo/10.png) | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Site/7-8-9-10.png)
Minha Conta | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Aplicativo/11.png) | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Site/11.png)
Alterar Senha | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Aplicativo/12.png) | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Site/12.png)
Documentos | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Aplicativo/13.png) | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Site/13.png)
Resumo do Boletim de Ocorrência | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Aplicativo/14.png) | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Site/14.png)
Dados da Vistoria | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Aplicativo/15.png) | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Site/15.png)
Danos Humanos | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Aplicativo/16.png) | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Site/16.png)
Relatório Fotográfico | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Aplicativo/17.png) | [visualizar](https://raw.githubusercontent.com/marcellocamara/TCC/master/ScreenShots/Site/17.png)
