<table>
<thead>
<tr>
  <th>

**trigger**

  </th>
  <th>

**snippet(JS)**

  </th>
  <th>

**snippet(TS)**

  </th>
</tr>
</thead>
<tbody>
<tr>
  <td><code>rcns⇥</code></td>
  <td>   

```js
constructor(props) {
  super(props)

  this.state = {
    
  }
}
```

  </td>
  <td>   

```ts
constructor(props: Props) {
  super(props)

  this.state = {
    
  }
}
```

  </td>
</tr>

<tr>
  <td><code>cdm⇥</code></td>
  <td>   

```js
componentDidMount() {

}
```

  </td>
  <td>   

```ts
componentDidMount(): void {

}
```

  </td>
</tr>

<tr>
  <td><code>cdu⇥</code></td>
  <td>   

```js
componentDidUpdate(prevProps, prevState, snapshot) {

}
```

  </td>
  <td>   

```ts
componentDidUpdate(prevProps: Props, prevState: State, snapshot: any): void {

}
```

  </td>
</tr>

<tr>
  <td><code>cdc⇥</code></td>
  <td>   

```js
componentDidCatch(error, info) {

}
```

  </td>
  <td>   

```ts
componentDidCatch(error: Error, info: ErrorInfo): void {

}
```

  </td>
</tr>

<tr>
  <td><code>cwu⇥</code></td>
  <td>   

```js
componentWillUnmount() {

}
```

  </td>
    <td>   

```ts
componentWillUnmount(): void {

}
```

  </td>
</tr>

<tr>
  <td><code>scu</code></td>
  <td>   

```js
shouldComponentUpdate(nextProps, nextState) {

}
```

  </td>
  <td>   

```ts
shouldComponentUpdate(nextProps: Props, nextState: State): boolean {

}
```

  </td>
</tr>



</tbody>
</table>
