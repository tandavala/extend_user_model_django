# extend user model django
O sistema de autenticação integrado do Django é ótimo. Na maioria das vezes, podemos usá-lo fora da caixa, economizando muito esforço de desenvolvimento e teste. Ele se encaixa na maioria dos casos de uso e é muito seguro. Mas às vezes precisamos fazer algum ajuste fino para caber em nosso aplicativo da Web.


Comumente, queremos armazenar mais alguns dados relacionados ao nosso usuário.
Se o seu aplicativo da Web tiver um apelo social, você poderá armazenar uma
pequena biografia, a localização do usuário e outras coisas desse tipo.

Neste tutorial, apresentarei as estratégias que você pode usar para
simplesmente estender o modelo de usuário padrão do Django, para que você não
precise implementar tudo do zero.
