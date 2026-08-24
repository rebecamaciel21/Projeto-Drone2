<!-- ===========================================================
     COMO USAR ESTE MODELO  (apague este bloco antes de entregar)

     1. Copie este arquivo para a RAIZ do seu repositório,
        do lado do index.html, com o nome exato: README.md
     2. Troque tudo que estiver entre colchetes [ ] pelos seus dados.
     3. Apague as linhas de instrução como esta.
     4. Confira no GitHub se o arquivo aparece formatado na página
        inicial do repositório. Se aparecer o texto cru, com os
        símbolos #, o nome do arquivo está errado.

     O critério 1.3 da rubrica avalia este arquivo. Para receber
     "Atende", ele precisa ter: seu nome, a turma, uma descrição
     do projeto e o link da página publicada.
     =========================================================== -->



Projeto prático da unidade curricular de , do curso Técnico em
Desenvolvimento de Sistemas — SESI/SENAI Itapeva.



| | |
|---|---|
|  | Rebeca Rodrigues Cardoso Maciel |
|  | 2°ano B |
|  | Rafael Ribas |
|  | 17/08/2026 |



Landing page de apresentação de , um drone agrícola fictício voltado à
pulverização e ao monitoramento de lavouras. O objetivo da página é convencer o
agricultor a agendar uma demonstração do produto.

O layout foi construído a partir de um protótipo no Figma, com HTML semântico e CSS,
sem frameworks.

> Gostei bastante de desenvolver esse projeto, pois pude praticar HTML e CSS e aprender mais sobre design e principalmente sobre responsividade.
Foi um projeto bem detalhado que me ajudou a perceber como esses pequenos detalhes podem fazer diferença no final. Fiquei satisfeita com o resultado final e com a identidade visual da AgroVant.


Link Vercel: https://projeto-drone2.vercel.app/



```
landing-page-drone/
├── index.html        página principal
├── README.md         este arquivo
├── css/
│   └── style.css     estilos do projeto
└── img/              imagens e vídeos
```



- [x] Menu (cabeçalho)
- [x] Hero section
- [x] Especificações
- [x] Vídeo do produto
- [x] Cards de benefícios
- [x] Depoimentos
- [x] Formulário de contato



-  — `header`, `main`, `section`, `footer`
-  com variáveis em `:root`
-  para os layouts
-  com abordagem e media queries
-  (`rem`, `%` e pixel) no lugar de medidas fixas



A página foi construída começando pelo celular. O CSS base atende telas pequenas e as
media queries acrescentam o comportamento das telas maiores, a partir de .

| Tela | Comportamento |
|---|---|
| Celular | O conteúdo se adapta à largura da tela, os cards de depoimentos ficam empilhados em uma única coluna e os textos e elementos são ajustados para facilitar a leitura. |
| Desktop |  O menu de navegação é exibido normalmente e os três cards de depoimentos ficam organizados lado a lado, aproveitando melhor o espaço disponível. |



```bash
git clone https://github.com/rebecamaciel21/Projeto-Drone2.git
cd Projeto Drone
```


- Protótipo do layout: material da disciplina
- Imagens e vídeos: material fornecido pelo professor
- Fontes: [Roboto]("https://fonts.googleapis.com"), via Google Fonts
---