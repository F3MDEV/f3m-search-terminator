<p align="center">
  <a href="https://f3m.pt/" rel="noopener" target="_blank"><img width="350" src="https://i.imgur.com/xIfYBjh.png" alt="F3M logo"></a></p>
</p>

<h1 align="center">F3M Search-terminator</h1>

<div align="center">

[React](https://reactjs.org/) component for faster and simpler web development.

<!--
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/mui-org/material-ui/blob/master/LICENSE)
[![npm latest package](https://img.shields.io/npm/v/@material-ui/core/latest.svg)](https://www.npmjs.com/package/@material-ui/core)
[![npm next package](https://img.shields.io/npm/v/@material-ui/core/next.svg)](https://www.npmjs.com/package/@material-ui/core)
[![npm downloads](https://img.shields.io/npm/dm/@material-ui/core.svg)](https://www.npmjs.com/package/@material-ui/core)
[![CircleCI](https://img.shields.io/circleci/project/github/mui-org/material-ui/next.svg)](https://app.circleci.com/pipelines/github/mui-org/material-ui?branch=next)
[![Coverage Status](https://img.shields.io/codecov/c/github/mui-org/material-ui/next.svg)](https://codecov.io/gh/mui-org/material-ui/branch/next)
[![Follow on Twitter](https://img.shields.io/twitter/follow/MaterialUI.svg?label=follow+Material-UI)](https://twitter.com/MaterialUI)
[![Dependabot Status](https://api.dependabot.com/badges/status?host=github&repo=mui-org/material-ui)](https://dependabot.com)
[![Average time to resolve an issue](https://isitmaintained.com/badge/resolution/mui-org/material-ui.svg)](https://isitmaintained.com/project/mui-org/material-ui 'Average time to resolve an issue')
[![Crowdin](https://badges.crowdin.net/material-ui-docs/localized.svg)](https://translate.material-ui.com/project/material-ui-docs)
[![Open Collective backers and sponsors](https://img.shields.io/opencollective/all/material-ui)](https://opencollective.com/material-ui) -->

</div>

## Installation

MpDS Search-Terminator is available as an [npm package](npm i f3m-search-terminator).

```sh
// with npm
npm i f3m-search-terminator

```

## Usage

Here is a quick example to get you started, **it's all you need**:

```tsx
import * as React from "react";
import F3MSearchTerminator from "f3m-search-terminator";

function App() {
  return (
    <F3MSearchTerminator placeholderInput="Search for gold!"></F3MSearchTerminator>
  );
}

ReactDOM.render(<App />, document.querySelector("#app"));
```

<h4>Props</h4>

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Description</th>
      <th>Default</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <span>aside</span>
      </td>
      <td>
        <div>
          <span>Attach elements to the left side of the input.</span>
        </div>
        <div>
          <div>
            <span>any</span>
          </div>
        </div>
      </td>
      <td>
        <span>-</span>
      </td>
    </tr>
    <tr>
      <td>
        <span>results</span>
      </td>
      <td>
        <div>
          <span>It shows the results of the search when it has something.</span>
        </div>
        <div>
          <div>
            <span>any</span>
          </div>
        </div>
      </td>
      <td>
        <span>
            <blockquote>
                <Table aria-label="simple table">
                    <TableBody>
                        <TableRow>
                        <TableCell component="td" scope="row" style={{ display: 'flex', alignItems: 'center' }}>
                        <Avatar alt="Cesária Costa" src="../componentAssets/account-circle.svg" style={{ marginRight: 10}} />
                            Cesária Costa
                        </blockquote>
                        </TableCell>
                        <TableCell>123456789</TableCell>
                        <TableCell>86 anos</TableCell>
                        </TableRow>
                    </TableBody>
                </Table>
            </blockquote>
        </span>
      </td>
    </tr>
    <tr>
      <td>
        <span>value</span>
      </td>
      <td>
        <div>
          <span>Value in the input.</span>
        </div>
        <div>
          <div>
            <span>any</span>
          </div>
        </div>
      </td>
      <td>
        <span>-</span>
      </td>
    </tr>
    <tr>
      <td>
        <span>color</span>
      </td>
      <td>
        <div>
          <span>Color of the input.</span>
        </div>
        <div>
          <div>
            <span>'primary' | 'secondary'</span>
         </div>
        </div>
      </td>
      <td>
        <span>"primary"</span>
      </td>
    </tr>
    <tr>
      <td>
        <span>label</span>
      </td>
      <td>
        <div>
          <span>Label of the input.</span>
        </div>
        <div>
          <div>
            <span>string</span>
          </div>
        </div>
      </td>
      <td>
        <span>'Search'</span>
      </td>
    </tr>
    <tr>
      <td>
        <span>size</span>
      </td>
      <td>
        <div>
          <span>Size of the input.</span>
        </div>
        <div>
          <div>
            <span>'medium' | 'small'</span>
          </div>
        </div>
      </td>
      <td>
        <span>'small'</span>
      </td>
    </tr>
    <tr>
      <td>
        <span>size</span>
      </td>
      <td>
        <div>
          <span>Size of the input.</span>
        </div>
        <div>
          <div>
            <span>'medium' | 'small'</span>
          </div>
        </div>
      </td>
      <td>
        <span>'small'</span>
      </td>
    </tr>
    <tr>
      <td>
        <span>variantTextfield</span>
      </td>
      <td>
        <div>
          <span>Variant of the textfield.</span>
        </div>
        <div>
          <div>
            <span>'filled' | 'outlined' | 'standard'</span>
          </div>
        </div>
      </td>
      <td>
        <span>'outlined'</span>
      </td>
    </tr>
    <tr>
      <td>
        <span>inputWidth</span>
      </td>
      <td>
        <div>
          <span>Width of the input.</span>
        </div>
        <div>
          <div>
            <span>number</span>
          </div>
        </div>
      </td>
      <td>
        <span>700</span>
      </td>
    </tr>
    <tr>
      <td>
        <span>backgroundColorInput</span>
      </td>
      <td>
        <div>
          <span>Background color of the input.</span>
        </div>
        <div>
          <div>
            <span>any</span>
          </div>
        </div>
      </td>
      <td>
        <span>-</span>
      </td>
    </tr>
    <tr>
      <td>
        <span>showFilters</span>
      </td>
      <td>
        <div>
          <span>Show or hide the filter panel and his content.</span>
        </div>
        <div>
          <div>
            <span>boolean</span>
          </div>
        </div>
      </td>
      <td>
        <span>true</span>
      </td>
    </tr>
    <tr>
      <td>
        <span>showEmptyStateSearch</span>
      </td>
      <td>
        <div>
          <span>Show or hide the empty state.</span>
        </div>
        <div>
          <div>
            <span>boolean</span>
          </div>
        </div>
      </td>
      <td>
        <span>false</span>
      </td>
    </tr>
    <tr>
      <td>
        <span>showResults</span>
      </td>
      <td>
        <div>
          <span>Show or hide the results.</span>
        </div>
        <div>
          <div>
            <span>boolean</span>
          </div>
        </div>
      </td>
      <td>
        <span>false</span>
      </td>
    </tr>
    <tr>
      <td>
        <span>placeholderInput</span>
      </td>
      <td>
        <div>
          <span>Placeholder Input</span>
        </div>
        <div>
          <div>
            <span>string</span>
          </div>
        </div>
      </td>
      <td>
        <span>"Search here!"</span>
      </td>
    </tr>
    <tr>
      <td>
        <span>inputLabelClasses</span>
      </td>
      <td>
        <div>
          <span>Classes of the input label</span>
        </div>
        <div>
          <div>
            <span>string</span>
          </div>
        </div>
      </td>
      <td>
        <span>-</span>
      </td>
    </tr>
    <tr>
      <td>
        <span>inputClasses</span>
      </td>
      <td>
        <div>
          <span>Classes of the input</span>
        </div>
        <div>
          <div>
            <span>string</span>
          </div>
        </div>
      </td>
      <td>
        <span>-</span>
      </td>
    </tr>
    <tr>
      <td>
        <span>startAdornmentInput</span>
      </td>
      <td>
        <div>
          <span>StartAdornment content.</span>
        </div>
        <div>
          <div>
            <span>any</span>
          </div>
        </div>
      </td>
      <td>
        <span>
            <blockquote>
                (
                <InputAdornment position="start">
                    <SearchIcon color="primary" fontSize="large" />
                </InputAdornment>
                )
            </blockquote>
        </span>
      </td>
    </tr>
    <tr>
      <td>
        <span>endAdornmentInput</span>
      </td>
      <td>
        <div>
          <span>EndAdornment content.</span>
        </div>
        <div>
          <div>
            <span>any</span>
          </div>
        </div>
      </td>
      <td>
        <span>
            <blockquote>
            (
                <>
                <InputAdornment position="end">
                    <IconButton
                    size="small">
                    <CloseIcon />
                    </IconButton>
                </InputAdornment>
                </>
            )
            </blockquote>
        </span>
      </td>
    </tr>
  </tbody>
</table>
<br>
Yes, it's really all you need to get started! Try it in:
[CodeSandbox](https://codesandbox.io/)
<br>

## License

No License. "(...) nobody else can copy, distribute, or modify your work without being at risk of take-downs, shake-downs, or litigation."
