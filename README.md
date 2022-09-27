<h1 align="center">
📄<br>Commit patterns(This is a translation of "iuricode/padroes-de-commits" if you want to see the original repository in portuquese
</h1>

<h1 align="center">
  <img src="gitcommit.png">
</h1>

According to the **Conventional Commits** documentation, Semantic Commits are a simple convention to use in commit messages. This convention defines a set of rules for creating an explicit commit history, which facilitates the creation of automated tools.

These commits will help you and your team to easily understand what changes were made to the code snippet that was committed.

This identification occurs through a word and emoji that identifies if that commit made is a code change, package update, documentation, visual change, test...

## 🦄 Type and Description

The semantic commit has the following structural elements (types), which inform the intent of your commit to the user of your code.

- `feat`- Commits of type feat indicate that your code snippet is including a **new feature** (relates to the MINOR of semantic versioning).

- `fix` - Fix commits indicate that your committed code snippet is **fixing a problem** (bug fix), (relates to the semantic versioning PATCH).

- `docs` - Commits like docs indicate that there have been **documentation changes**, such as in the Readme of your repository. (Does not include code changes).

- `test` - Test-type commits are used when **changes to tests** are made, either by creating, changing or deleting unit tests. (Does not include code changes)

- `build` - Build commits are used when modifications are made to **build files and dependencies**.

- `perf` - Commits of type perf serve to identify any code changes that are related to **performance**.

- `style` - Style commits indicate that there were changes regarding **code formatting**, semicolons, trailing spaces, lint... (Does not include code changes).

- `refactor` - Refactor type commits refer to changes due to **refactorings that do not change its functionality**, such as, for example, a change in the format in which a certain part of the screen is processed, but which kept the same functionality, or performance improvements due to a code review.

- `chore` - Chore commits indicate build **task updates**, admin settings, packages... such as adding a package in gitignore. (Does not include code changes)

- `ci` - Commits of the type that indicate changes related to **continuous integration** (*continuous integration*).

## ☑️ Recommendations
- Add a title consistent with the title of the content;
- We recommend that the first line should have a maximum of 4 words;
- To describe in detail, use the commit description;
- Use an emoji at the beginning of the commit message representing the commit;
- A link needs to be added in its most authentic form, that is: without link shorteners and affiliate links;

## 💈 Emoji patterns

<table>
  <thead>
    <tr>
      <th>Commit type</th>
      <th>Emojis</th>
      <th>Keyword</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>Accessibility</td>
      <td>♿ <code>:wheelchair:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Adding a test</td>
      <td>✅ <code>:white_check_mark:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Adding a dependency</td>
      <td>➕ <code>:heavy_plus_sign:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Code review changes</td>
      <td>👌 <code>:ok_hand:</code></td>
      <td><code>style</code></td>
    </tr>
    <tr>
      <td>Animations and transitions</td>
      <td>💫 <code>:dizzy:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Bugfix</td>
      <td>🐛 <code>:bug:</code></td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Comments</td>
      <td>💡 <code>:bulb:</code></td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>Initial commit</td>
      <td>🎉 <code>:tada:</code></td>
      <td><code>init</code></td>
    </tr>
    <tr>
      <td>Settings</td>
      <td>🔧 <code>:wrench:</code></td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>Deploy</td>
      <td>🚀 <code>:rocket:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Documentation</td>
      <td>📚 <code>:books:</code></td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>In progress</td>
      <td>🚧 <code>:construction:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Interface styling</td>
      <td>💄 <code>:lipstick:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Infrastructure</td>
      <td>🧱 <code>:bricks:</code></td>
      <td><code>ci</code></td>
    </tr>
    <tr>
      <td>List of ideas (tasks)</td>
      <td>🔜 <code> :soon: </code></td>
      <td></td>
    </tr>
    <tr>
      <td>Move/Rename</td>
      <td>🚚 <code>:truck:</code></td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>New feature</td>
      <td>✨ <code>:sparkles:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Package.json in JS</td>
      <td>📦 <code>:package:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Performance</td>
      <td>⚡ <code>:zap:</code></td>
      <td><code>perf</code></td>
    </tr>
    <tr>
        <td>Refactoring</td>
        <td>♻️ <code>:recycle:</code></td>
        <td><code>refactor</code></td>
    </tr>
    <tr>
      <td>Removing a file</td>
      <td>🔥 <code>:fire:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Removing a dependency</td>
      <td>➖ <code>:heavy_minus_sign:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Responsiveness</td>
      <td>📱 <code>:iphone:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Reversing changes</td>
      <td>💥 <code>:boom:</code></td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Safety</td>
      <td>🔒️ <code>:lock:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>SEO</td>
      <td>🔍️ <code>:mag:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Version tag</td>
      <td>🔖 <code>:bookmark:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Pass test</td>
      <td>✔️ <code>:heavy_check_mark:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Tests</td>
      <td>🧪 <code>:test_tube:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Text</td>
      <td>📝 <code>:pencil:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Typing</td>
      <td>🏷️ <code>:label:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Error handling</td>
      <td>🥅 <code>:goal_net:</code></td>
      <td></td>
    </tr>
  </tbody>
</table>

## 💻 Examples
<table>
  <thead>
    <tr>
      <th>Git command</th>
      <th>Result on GitHub</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>
        <code>git commit -m ":tada: Initial commit"</code>
      </td>
      <td>🎉 Initial commit</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":books: docs: README update"</code>
      </td>
      <td>📚 docs: README update</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bug: fix: Infinite loop on line 50"</code>
      </td>
      <td>🐛 fix: Infinite loop on line 50</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":sparkles: feat: Login page"</code>
      </td>
      <td>✨ feat: Login page</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bricks: ci: Modification in Dockerfile"</code>
      </td>
      <td>🧱 ci: Modification in Dockerfile</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":recycle: refactor: Passing to arrow functions"</code>
      </td>
      <td>♻️ refactor: Passing to arrow functions</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":zap: perf: Melhoria no tempo de resposta"</code>
      </td>
      <td>⚡ perf: Melhoria no tempo de resposta</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":boom: fix: Revertendo mudanças ineficientes"</code>
      </td>
      <td>💥 fix: Revertendo mudanças ineficientes</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":lipstick: feat: Estilizaçao CSS do formulario"</code>
      </td>
      <td>💄 feat: Estilizaçao CSS do formulario</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":test_tube: test: Criando novo teste"</code>
      </td>
      <td>🧪 test: Criando novo teste</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bulb: docs: Comentários sobre a função LoremIpsum( )"</code>
      </td>
      <td>💡 docs: Comentários sobre a função LoremIpsum( )</td>
    </tr>
  </tbody>
</table>

<br>[🔝 Voltar ao topo](#padrões-de-commits-) <br>
