<div> 
<p><a href="https://github.com/JosiTubaroski/WEB-API-com-.NET-8-e-SQL-Server">Home</a></p>
</div> 

<img src="https://github.com/JosiTubaroski/Controllers_Services/blob/main/img/01_Fx_Controller_Interface_Service_2.jpg"/>

# End-Point: Editar Autor / Excluir Autor

1. Para editar autor vamos precisar de um novo Dto (Data Transfer Object), na Pasta Dto criar a classe 'AutorEdicaoDto.cs'

<img src="https://github.com/JosiTubaroski/.NET8_Atualizar_Autor/blob/main/img/08_AutorEdicaoDto.png"/>

2. Criar os métodos <b>EditarAutor</b> e <b>ExcluirAutor</b> na classe <b>IAutorInterface.cs</b>

<img src="https://github.com/JosiTubaroski/.NET8_Atualizar_Autor/blob/main/img/09_Metodos_Interface.png"/>

3. Incluir os metodos na <b>AutorService</b>, selecionar <b>implementar interface</b> para atualizar os métodos

<img src="https://github.com/JosiTubaroski/.NET8_Atualizar_Autor/blob/main/img/10_Editar_Excluir_Autor_Service.png"/>

4. Desenvolver <b>ExcluirAutor</b> na <b>AutorService.cs</b>

<img src="https://github.com/JosiTubaroski/.NET8_Atualizar_Autor/blob/main/img/11_Metodo_ExcluirAutor_Service.png"/>

5. Desenvolver <b>EditarAutor</b> na <b>AutorService.cs</b>

<img src="https://github.com/JosiTubaroski/.NET8_Atualizar_Autor/blob/main/img/12_Metodo_Editar_Service.png"/>

6. Incluir os métodos <b>EditarAutor</b>, <b>ExcluirAutor</b> na <b>AutorController</b>.

<img src="https://github.com/JosiTubaroski/.NET8_Atualizar_Autor/blob/main/img/13_Editar_Excluir_Controller.png"/>

7. Executar o Projeto e Testar o EditarAutor

<img src="https://github.com/JosiTubaroski/.NET8_Atualizar_Autor/blob/main/img/14_Teste_EditarAutor_Request.png"/>

<img src="https://github.com/JosiTubaroski/.NET8_Atualizar_Autor/blob/main/img/15_Teste_EditarAutor_Response.png"/>

<img src="https://github.com/JosiTubaroski/.NET8_Atualizar_Autor/blob/main/img/16_EditarAutor_Response.png"/>

8. Executar o Projeto e Testar o ExcluirAutor
