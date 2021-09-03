# react - print - nb

react print 
### example:
___
#### Calling from class components

```
import React from "react";
import ReactPrintNb from "react-print-nb";
export default class App extends React.Component {
  render() {
    return (
      <div>
        <button
          onClick={() => {
            this.refs.test.onPrint();
          }}
        >
          print
        </button>
        <ReactPrintNb ref="test">
          <p>
            <h1>you are beatiful</h1>
           <img src="https://img1.baidu.com/it/u=425067323,3523178242&fm=253&fmt=auto&app=120&f=JPEG?w=500&h=500"/>
          </p>
        </ReactPrintNb>
      </div>
    );
  }
}

```
### Demo
___
[![Edit react - to - print](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/nifty-sunset-wm7f2)
