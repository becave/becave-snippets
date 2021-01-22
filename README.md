# styled-components component snippet

### Usage - Start typing _sc_

<br/>

```json
{
  "styled-component": {
    "prefix": ["sc"],
    "body": [
      "export const ${1:Component} = styled${2: .div or (Component) }`",
      "\t$0",
      "`;",
      "${1:Component}.displayName = '${1:Component}';"
    ],
    "description": "An exported styled component with a displayName"
  }
```

# Storybook story stippet

### Usage - Start typing _st_

<br/>

```json
  "Storybook story": {
    "prefix": ["st"],
    "body": [
      "import faker from 'faker';",
      "import ${1:Component} from './${1:Component}';",
      "",
      "export default {",
      "  title: '${1:Component}',",
      "  component: ${1:Component},",
      "};",
      "",
      "export const Basic = (args: any) => <${1:Component} {...args} />;",
      "",
      "Basic.args = {",
      "  src: faker.image.people(),",
      "};"
    ],
    "description": "A Storybook story template"
  }
}
```
