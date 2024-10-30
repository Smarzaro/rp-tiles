# *Tiles* para Rio Paranaíba-MG-Brasil  


Este repositório contém *tiles* gerados a partir de um ortomosaico da cidade de Rio Paranaíba. Os tiles foram criados para serem utilizados como camada de imagem de fundo em softwares de mapeamento como o [JOSM](https://josm.openstreetmap.de/). O ortomosaico utilizado tem resolução de 25cm/pixel e foi produzido pelo capítulo [Youthmappers UFV](https://www.instagram.com/youthmappers.ufv/), tendo como responsável o prof. Rodrigo Smarzaro. O Youthmappers UFV é um projeto de extensão da [Universidade Federal de Viçosa](https://www.ufv.br/campus-rio-paranaiba/) e faz parte da rede [Youthmappers](https://www.youthmappers.org/).

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d6/YouthMappersUFV_transparente.png/240px-YouthMappersUFV_transparente.png" alt="Youthmappers Logo" width="200">
</p>

## Configuração das *Tiles* no iD como Imagem de Fundo

Para utilizar os tiles como camada de fundo no editor iD, siga estas etapas:

1. **Abrir o editor iD** e acessar o menu de **Configurações de Fundo** clicando no ícone de mapa à direita ou pressionando **B** no teclado.

2. **Adicionar uma URL personalizada** para os tiles:
   - No painel de fundo, role até a seção "Imagens Personalizadas" e clique em **Custom** (ou "Personalizado").

3. **Inserir a URL dos tiles**: 
   - Na caixa que aparece, insira a URL no formato:
     
     ```
     https://smarzaro.github.io/rp-tiles/{zoom}/{x}/{-y}.png
     ```

4. **Nome da Camada**: Opcionalmente, insira um nome para a camada, como "Ortomosaico Rio Paranaíba".

5. **Aplicar as Configurações**: Clique fora da caixa de URL para aplicar a nova camada como imagem de fundo.

Agora, a camada dos *tiles* será exibida como plano de fundo no editor iD. Você pode alternar entre diferentes camadas de fundo usando o atalho **CTRL + B**.
         
## Configuração das *Tiles* no JOSM como Imagem de Fundo

Para utilizar os *tiles* como camada de fundo no JOSM, siga as etapas abaixo:

1.  **Abrir o JOSM** e acessar o menu **Imagery** > **Imagery Preferences**.
    
2.  **Adicionar uma nova camada TMS** clicando em **+TMS**.
    
3.  **Configurar a URL da camada**: Insira a URL dos tiles no seguinte formato:
     
    `tms[15,20]:https://smarzaro.github.io/rp-tiles/{zoom}/{x}/{-y}.png` 
    
4.  **Nome da Camada**: Dê um nome à camada, como "Ortomosaico Rio Paranaíba".
    
5.  Clique em **OK**. A camada estará disponível como imagem de fundo.

## Licença e Permissão para Uso

Este ortomosaico foi criado por **Rodrigo Smarzaro** e está licenciado sob a **Creative Commons Atribuição 4.0 (CC BY 4.0)**. Você é livre para:
- **Compartilhar** — copiar e redistribuir o material em qualquer suporte ou formato.
- **Adaptar** — remixar, transformar, e criar a partir do material para qualquer finalidade, inclusive comercial.

### Atribuição
Para uso deste ortomosaico, a seguinte atribuição é necessária:
> Ortoimagem da Cidade de Rio Paranaíba, de Rodrigo Smarzaro, licenciada sob CC BY 4.0. [Link para a licença](https://creativecommons.org/licenses/by/4.0/).

### Permissão específica para uso no OpenStreetMap
Este ortomosaico pode ser utilizado como base para mapeamento no OpenStreetMap. Os dados derivados podem ser publicados e redistribuídos sob a **Open Database License (ODbL)**.

Para mais informações, consulte [Creative Commons BY 4.0](https://creativecommons.org/licenses/by/4.0/).
