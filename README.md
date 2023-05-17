<a href=https://www.php.net >php</a> 
<a href=https://laravel.com/docs/10.x >laravel </a> 
         -- Passo a Passo --

Proposta: 
<br>
A proposta inicial do projeto é desenvolvermos 3 serviços que se 
comunicam entre si. Adicionaremos complexidade de acordo com o an
damento da turma.
<br>
1- Ter um ambiente para executar a tarefa (meu caso: vscode)
<br>
2- Criar um prjeto em laravel. Comando: composer create-project laravel/laravel Escola-Api
<br>
3- No arquivo web criamos as rotas:  O /hello exibe a mensagem 'Hello Word' e a / aponta os padsde url 
          
          -- ROTAS --
<br>
Route::get('/', function () {
    return view('welcome');
});
<br>
Route::get('/', function () {
    return '{"hello_url": "/hello"}';
});
<br>
Route::get('/hello', function () { 
    return 'Hello Word'; 
}); 




