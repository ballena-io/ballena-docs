# Contribuir

##  **\*\* IN PROGRESS** \*\*

[ballena.io](https://ballena.io/) está abierto a colaboradores y el equipo de desarrollo te muestra los pasos para que puedas comenzar a contribuir en este proyecto de código abierto. 

Antes de comenzar cualquier desarrollo, recomendamos que te unas a nuestros canales de [Discord](https://discord.gg/ydRbEAaqqc) y que te pongas en contacto con nuestro equipo de desarrollo en el canal **\#dev**.

## Configura tu entorno de desarrollo

1. Bifurca \(Fork\) el repositorio y agrega un [control remoto upstream](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/configuring-a-remote-for-a-fork). Ej.

```bash
$ git remote add upstream git@github.com:ballena-io/ballena-frontend.git
```

2. Asegúrate de tener la última versión de la rama predeterminada \( `dev` o `master` \).

```bash
$ git checkout develop
$ git pull upstream develop
```

3. Crea tu propia rama e instala dependencias.

```bash
$ git checkout -b branch-name
$ yarn
```



## Reglas Coding

Intentamos mantener la mayor consistencia posible entre cada uno de nuestros repositorios. Tu solicitud de extracción tiene más posibilidades de ser aceptada si sigue algunas de las siguientes reglas y desarrollas código de alta calidad.



#### Utiliza el UIKit

{% hint style="warning" %}
Verifica el [UI Kit](https://github.com/ballena-io/ballena-uikit) antes de comenzar a hacer cualquier cosa. Ya se han creado muchos componentes y no queremos que pierdas el tiempo reinventando la rueda.
{% endhint %}

Si es necesario crear una variante de un componente, utilice el componente correspondiente en el UI Kit como base. Por ejemplo:

```javascript
import styled from 'styled-components'
import { Button } from '@@ballena-io/ballena-uikit'

const NewButtonVariant = styled(Button)`
  // custom styles here
`
```

#### 

#### Utiliza las herramientas

La mayoría de nuestros repositorios utilizan [Typescript](https://www.typescriptlang.org/docs), [ESLint](https://eslint.org/docs/user-guide/getting-started) y [Prettier](https://prettier.io/). Asegúrate de estar familiarizado con las mejores prácticas de Typescript y habilita un complemento ESLint y Prettier para tu IDE.

{% hint style="warning" %}
Asegúrate de que tu código esté formateado con Prettier y que no tenga ningún error de ESLint antes de enviar un Pull Request.
{% endhint %}



#### Buenas prácticas

* Mantén los componentes lo más pequeños y ["dumb"](https://en.wikipedia.org/wiki/Pure_function) posible. 
* Utiliza la [Composition sobre Inheritance](https://reactjs.org/docs/composition-vs-inheritance.html). 
* Ten en cuenta que tu código será leído y mantenido por otros desarrolladores. Hazlo lo más claro y fácil de actualizar posible.

## Committing

Nuestros mensajes de confirmación \(Commit\) siguen los [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) mediante [commitlint](https://commitlint.js.org/#/).‌

| Tipo | Descripción |
| :--- | :--- |
| **build** | Changes that affect the build system or external dependencies \(example scopes: gulp, broccoli, npm\) |
| **ci** | Changes to our CI configuration files and scripts \(example scopes: Travis, Circle, BrowserStack, SauceLabs\) |
| **docs** | Documentation only changes |
| **feat** | A new feature |
| **fix** | A bug fix |
| **perf** | A code change that improves performance |
| **refactor** | A code change that neither fixes a bug nor adds a feature |
| **style** | Changes that do not affect the meaning of the code \(white-space, formatting, missing semi-colons, etc\) |
| **test** | Adding missing tests or correcting existing tests |

_Más info en_ [_Angular's guidelines_](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#type)_._

## _​_Crea tu pull request 

Tu código está listo para ser enviado a revisión, felicitaciones🥳_._

* All pull requests **must** have a description of what the PR is trying to accomplish.
* Keep pull requests **as small as possible**. Larger pull requests should be broken up into smaller chunks with a dedicated base branch. Please tag the PR's that are merging into your base branch with the `epic` tag.
* If possible self-review your PR and **add comments** where additional clarification is needed.

{% hint style="info" %}
Cree un [draft PR](https://github.blog/2019-02-14-introducing-draft-pull-requests/) \(borrador\) lo antes posible para que podamos ver tu progreso.
{% endhint %}



\*\*\*\*

