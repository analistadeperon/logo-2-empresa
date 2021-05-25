# logo-2-empresa

<hello name="{{ name }}"></hello>
<p>
  Start # https://github.com/analistadeperon :)
</p>

<link href="//maxcdn.bootstrapcdn.com/bootstrap/3.3.0/css/bootstrap.min.css" rel="stylesheet" id="bootstrap-css">
<script src="//maxcdn.bootstrapcdn.com/bootstrap/3.3.0/js/bootstrap.min.js"></script>
<script src="//code.jquery.com/jquery-1.11.1.min.js"></script>
<!------ Include the above in your HEAD tag ---------->

<!--
    you can substitue the span of reauth email for a input with the email and
    include the remember me checkbox
    -->
    <div class="container">
        <div class="card card-container">
            <!-- <img class="profile-img-card" src="//lh3.googleusercontent.com/-6V8xOA6M7BA/AAAAAAAAAAI/AAAAAAAAAAA/rzlHcD0KYwo/photo.jpg?sz=120" alt="" /> -->
            <img id="profile-img" class="profile-img-card" src="https://storage.googleapis.com/atados-v3/project/institutosorrirparavida/programador-1.jpeg" />
            <p id="profile-name" class="profile-name-card"></p>
            <form class="form-signin">
                <span id="reauth-email" class="reauth-email"></span>
                <input type="text" id="nome" class="form-control" placeholder="Nome" 
                required autofocus>
                 <input type="text" id="CPF" class="form-control" placeholder="CPF" 
                required autofocus>
                 <input type="text" id="confirma senha" class="form-control" placeholder="Confirme a senha" 
                required autofocus>
                                 <input type="password" id="senha" class="form-control" placeholder="Senha" required>
                <div id="remember" class="checkbox">
                  <input type="text" id="digite seu login" class="form-control" placeholder="Digite seu Login" 
                required autofocus>
                <input type="text" id="digite sua cidade" class="form-control" placeholder="Digite sua Cidade" 
                required autofocus>
                <input type="text" id="digite seu contato" class="form-control" placeholder="Digite seu Contato" 
                required autofocus>
                    <label>
                        <input type="checkbox" value="remember-me"> Lembre-se!
                    </label>
                </div>
                <button class="btn btn-lg btn-primary btn-block btn-signin" type="submit">Entrar</button>
                <button class="btn btn-lg btn-primary btn-block btn-signin" type="submit">Login</button>
            </form><!-- /form -->
            <a href="#" class="forgot-password">
                 Esqueceu a senha?
                 Recadastre  a senha!
                 <input type="text" id="digite nova senha" class="form-control" placeholder="Digite nova senha" 
                required autofocus>
                 <button class="btn btn-lg btn-primary btn-block btn-signin" type="submit">Confitme aqui</button>
            </a>
        </div><!-- /card-container -->
    </div><!-- /container -->
    
