[![license][licenca-badge]][LICENSE]

### Apresentação

Esta modificação foi desenvolvida no formato OCMOD (substituto do VQMOD), e adiciona a possibilidade de instalar extensões sem utilizar o FTP no OpenCart, porém, mantém a função FTP funcionando.

Uma das grandes vantagens desta modificação é permitir que, ao montar sua loja em ambiente local (no seu pc ou servidor local), você possa instalar extensões através do Instalador de Extensões do OpenCart, sem a necessidade da utilização do FTP.

#### Importante

A partir da versão 3.0.0.0 do OpenCart, esse recurso se tornou nativo, dispensando a utilização desta modificação.

### Instalação

 1. Baixe a modificação no link: https://github.com/opencartbrasil/instalador-sem-ftp/archive/master.zip
 2. Ao baixar, descompacte o conteúdo do arquivo zip e localize o arquivo "instalador-sem-ftp.ocmod.xml".
 3. Na administração da loja acesse o menu **Extensões→Instalador** (Extensions→Installer).
 4. Na página do instalador, clique no botão **Upload**, selecione o arquivo 'instalador-sem-ftp.ocmod.xml', e aguarde a conclusão da instalação automática.
 5. Após a instalação, acesse o menu **Extensões→Modificações** (Extensions→Modifications) e clique no botão **Atualizar** (Refresh), para que a modificação seja adicionada na loja, lembrando que não é o botão "Atualizar" do navegador, e sim o botão "Atualizar" na cor azul ao lado do botão laranja e vermelho na tela do próprio OpenCart.

### Configuração

Acesse a administração da loja e vá no menu **Configurações→Lojas** (System→Settings), clique no botão **Editar** (Edit), clique na ba **FTP**, localize o campo "**Ativar FTP?**" (Enable FTP), marque a opção "**Não**" (No), e clique no botão **Salvar** (Save).

### Desinstalação

Para desinstalar a modificação, na administração da loja, acesse o menu **Extensões→Modificações** (Extensions→Modifications), selecione a modificação com o nome '**Instalador sem FTP**', clique no botão **Excluir** (Delete), e depois no botão **Atualizar** (Refresh).

### Atualização

Acesse a administração da loja e execute o procedimento de Desinstalação, depois execute o procedimento de Instalação.

### Dúvidas

O OCMOD (OpenCart Modification) é nativo do OpenCart, ou seja, não é necessário instalar nenhum complemento no OpenCart para utilizar modificações ou extensões no formato OCMOD, para mais informações sobre o OCMOD, segue o link para mais informações:

https://github.com/opencart/opencart/wiki/Modification-System

### O arquivo alterado virtualmente através do OCMOD é:

admin/controller/extension/**installer.php**

[licenca-badge]: https://img.shields.io/badge/licença-GPLv3-blue.svg
[LICENSE]: ./LICENSE
