<h2 align="center">LaraCurrency</h2>

<p align="center">
    <a href="#">
        <img alt="License" src="https://img.shields.io/github/license/Weavous/LaraCurrency">
    </a>
    <a href="#">
        <img alt="Languages" src="https://img.shields.io/github/languages/count/Weavous/LaraCurrency">
    </a>
    <a href="#">
        <img alt="Last Commit" src="https://img.shields.io/github/last-commit/Weavous/LaraCurrency">
    </a>
</p>

<p align="center">Development of an application to display currencies exchange rates</p>

<h4 align="center">Instructions <a href="https://github.com/emsventura/tech_challenge">🔗</a></h4>

<p align="center">Instructions for developing the application can be found in the icon above.</p>

<h4 align="center">Installation ⚙️</h4>

<h6 align="center"><a href="https://iconscout.com">✔️</a> Requirements</h6>

<p align="center">
    <a href="https://www.php.net"><img width="10%" src="https://cdn.iconscout.com/icon/free/png-256/php-3629567-3032350.png" alt="PHP Logo"></a>
    <a href="https://nodejs.org"><img width="10%" src="https://cdn.iconscout.com/icon/free/png-256/node-js-1-1174935.png" alt="Node Logo"></a>
    <a href="https://www.mysql.com"><img width="10%" src="https://cdn.iconscout.com/icon/free/png-256/mysql-3628940-3030165.png" alt="MySQL Logo"></a>
    <a href="https://vuejs.org"><img width="10%" src="https://cdn.iconscout.com/icon/free/png-256/vue-282497.png" alt="Vue Logo"></a>
    <a href="https://git-scm.com"><img width="10%" src="https://cdn.iconscout.com/icon/free/png-256/git-16-1175195.png" alt="Git Logo"></a>
    <a href="https://getcomposer.org"><img width="10%" src="https://cdn.iconscout.com/icon/free/png-256/composer-285363.png" alt="Composer Logo"></a>
</p>

```typescript
    return [
        {
            dependency: "PHP",
            url: "https://www.php.net",
            version: 7.4.21,
            img: "https://cdn.iconscout.com/icon/free/png-256/php-3629567-3032350.png"
        },
        {
            dependency: "Node",
            url: "https://nodejs.org",
            version: 16.4.1,
            img: "https://cdn.iconscout.com/icon/free/png-256/node-js-1-1174935.png"
        },
        {
            dependency: "MySQL",
            url: "https://www.mysql.com",
            version: 8.0.25,
            img: "https://cdn.iconscout.com/icon/free/png-256/mysql-3628940-3030165.png"
        },
        {
            dependency: "Vue",
            url: "https://vuejs.org",
            version: 2,
            img: "https://cdn.iconscout.com/icon/free/png-256/vue-282497.png"
        },
        {
            dependency: "Git",
            url: "https://git-scm.com",
            version:  2.32.0,
            img: "https://cdn.iconscout.com/icon/free/png-256/git-16-1175195.png"
        },
        {
            dependency: "Composer",
            url: "https://getcomposer.org",
            version: 2.1.3,
            img: "https://cdn.iconscout.com/icon/free/png-256/composer-285363.png"
        }
    ];
```

<h6 align="center">Backend 🛰</h6>

```bash
    composer create-project laravel/laravel backend
```

<h6 align="center">Storage</h6>

```sql
    CREATE DATABASE custom_webquarto_laravel_currency_application;
```

Next, add the following database configuration information

```txt
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=<database-name>
    DB_USERNAME=<database-username>
    DB_PASSWORD=<database-password>
```

<h6 align="center">JWT Guide Link<a href="https://www.avyatech.com/rest-api-with-laravel-8-using-jwt-token">🔐</a></h6>

<p align="center">Guide link to implement JSON Web Token (JWT) authentication</p>

<h6 align="center">Controllers</h6>

```bash
    php artisan make:controller AwesomeAPIController
```

<h6 align="center">Seeders</h6>

```bash
    php artisan make:seeder UserSeeder
```

<h6 align="center">Tests</h6>

```bash
    php artisan make:test JWTAuthTest
```

<span>Edit `backend\phpunit.xml`, setting `DB_CONNECTION` and `DB_DATABASE` values</span>

<h6 align="center">Frontend</h6>

```bash
    vue init webpack-simple frontend
```

```bash
    npm	install	axios --save
```

```bash
    npm install vue-router --save
```

<h6 align="center">Launch 🚀</h6>

```bash
    git clone https://github.com/Weavous/LaraVueCurrency
```

```bash
    cd LaraVueCurrency
```

<h6 align="center">Set up Backend Application 🚀</h6>

```bash
    cd backend
```

```bash
    cp .env.example .env
```

<span>You must specify the environment configuration in `.env` file</span>

```bash
    composer i
```

```bash
    php artisan key:generate
```

```bash
    php artisan migrate:fresh --seed
```

```bash
    php artisan serve
```

<h6 align="center">Set up Frontend Application 🚀</h6>

```bash
    cd frontend
```

```bash
    npm i
```

```bash
    npm run dev
```

<h6 align="center">Example User</h6>

```typescript
    return {
        email: "johndoe@example.com",
        password: "secret"
    }
```

<p align="center">4 folder structures to organize your React & React Native project <a href="https://reboot.studio/blog/folder-structures-to-organize-react-project">💾</a></p>

<h6>⚠️ Atenção - Possívels Erros</h6>

* A porta esperada para enviar as requisições é `8000`, se outra for estabelecida, alterar o conteúdo de `baseURL` em `frontend\src\services\http.js`.

* Caso ocorra algum erro na instalação das dependências do `Laravel` através do `Composer`, deve-se habilitar as extensões presentes no arquivo de configuração `php.ini`.

* O local do arquivo de configuração `php.ini` pode ser visualizado digitando-se `php --ini` no terminal.

* Caso ocorra um erro relacionado ao certificado SSL ao efetuar as requisições para o serviço externo, retornando uma mensagem de erro semelhante à essa `cURL error 60: SSL certificate problem: unable to get local issuer certificate`, pode-se resolver através da resposta presente em `https://stackoverflow.com/questions/24611640/curl-60-ssl-certificate-problem-unable-to-get-local-issuer-certificate`

<h6>Dúvidas ❔</h6>

* Quaisquer dúvidas ou sugestões quanto ao projeto, entrar em contato com <wesleyfloresterres@gmail.com>.