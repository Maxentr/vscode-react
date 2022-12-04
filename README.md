# VS Code React and Next snippets

This extension contains code TypeScript snippets for [React][react] and [Next 13][next]. Based on the awesome [babel-sublime-snippets][babelsublime] package.

This is a fork of [vscode-react extension][fork].

<img src="images/example.gif" alt="example" width="70%"/>

## Supported languages (file extensions)

- TypeScript (.ts)
- TypeScript React (.tsx)

## Usage

Type one of the following snippets, press `tab`, and the snippet unfolds. If the snippet has multiple tab stops, you can navigate between them with `tab`.

## Snippets

### Components

All components snippets start with `r` for React and `n` for Next respectively. They all end with `c` for Component.

| Trigger | Content                            |
| ------: | ---------------------------------- |
|   `rsc` | React Stateless Component          |
|  `rsfc` | React Stateless Function Component |
|  `ncsc` | Next Client Stateless Component    |
| `ncsfc` | Next Client Stateless Function     |

### Hooks

All hooks start with `use` followed by first letter of the hook name.

| Trigger | Content    |
| ------: | ---------- |
|  `uses` | useState   |
|  `usee` | useEffect  |
|  `user` | useReducer |
|  `usec` | useContext |

[fork]: https://github.com/xabikos/vscode-react
[react]: https://reactjs.org/
[next]: https://nextjs.org/
[babelsublime]: https://github.com/babel/babel-sublime-snippets
