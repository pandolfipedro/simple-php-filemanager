# simple-php-filemanager

Gerenciador de arquivos simples interativo.

Apenas faça o upload do index.php!

Configure as opções editando o arquivo

//Opções de Segurança
$allow_delete = false; // Defina como false para desativar o botão de exclusão e excluir a solicitação POST.
$allow_upload = false; // Defina como true para permitir o upload de arquivos
$allow_create_folder = false; // Defina como false para desativar a criação de pasta
$allow_direct_link = true; // Defina como false para permitir apenas downloads e não link direto
$allow_show_folders = false; // Defina como false para ocultar todos os subdiretórios

$hidden_patterns = ['*.php','.*']; // Extensões ocultas no índice do diretório

$PASSWORD = '';  // Defina a senha, para acessar o gerenciador de arquivos ... (opcional)


Edite o titulo do site em <title>
