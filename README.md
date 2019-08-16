<p align="center">
 :baby:
</p>

<h2 align="center">
  <strong>
    Bebe Styled
  </strong>
</h2>

<p align="center">
  <a href="https://github.com/deividmfl/bebe-styled/issues">Feature</a>
  ·
  <a href="https://github.com/deividmfl/bebe-styled/issues">Report</a>

</p>

## Navigation

- [Navigation](#navigation)
- [Get started](#get-started)
- [Included](#included)
- [Documentation](#documentation)
- [License](#license)

## Get started

- Clone the repo: `git clone https://github.com/deividmfl/bebe-styled.git`
<!-- - With [yarn](https://yarnpkg.com/): `yarn add bebe-styled`
- With [npm](https://www.npmjs.com/): `npm install bebe-styled` -->

## Included

```text
bebe-styled/
└── src/
    ├── Col/
    │   ├── Col.js
    |   ├── index.js
    |   ├── StyledComponents.js
    ├── Collapse/
    │   ├── Collapse.js
    |   ├── index.js
    |   ├── StyledComponents.js
    ├── Container/
    │   ├── Container.js
    |   ├── index.js
    |   ├── StyledComponents.js
    ├── Nav/
    │   ├── Nav.js
    |   ├── index.js
    |   ├── StyledComponents.js
    ├── Navbar/
    │   ├── Navbar.js
    |   ├── index.js
    |   ├── StyledComponents.js
    ├── NavbarBrand/
    │   ├── NavbarBrand.js
    |   ├── index.js
    |   ├── StyledComponents.js
    ├── NavbarToggler/
    │   ├── NavbarToggler.js
    |   ├── index.js
    |   ├── StyledComponents.js
    ├── Row/
    │   ├── Row.js
    |   ├── index.js
    |   ├── StyledComponents.js
    ├── index.js
```

## Documentation

<h3>
  <strong>Col</strong>
</h3>

<p>the column goes from 1 to 12, and the container has a maximum of 960px.</p>

<h4>
  <strong>Example</strong>
</h4>

```text
  <Container>
    <Row>
      <Col col="1">col1</Col>
      <Col col="11">col11</Col>
    </Row>
  </Container>
```
<br>
<div style="background-color: #f7fbf1; color:black; padding: 1rem;">
  <h3 align="center">
    -- Col1 -- | ---------------------- Col11 ----------------------
    <br>
    <br>
    ---- Col2 ---- | -------------------- Col10 --------------------
    <br>
    <br>
    ------ Col3 ------ | ------------------ Col09 ------------------
    <br>
    <br>
    -------- Col4 -------- | ---------------- Col08 ----------------
    <br>
    <br>
    ---------- Col5 ---------- | -------------- Col07 --------------
    <br>
    <br>
    ------------ Col6 -------------- | ------------ Col6 ------------
  </h3>
</div>

<h3>
  <strong>Collapse</strong>
</h3>

<h4>
  <strong>Example</strong>
</h4>

```text
  <Collapse>

  </Collapse>
```

<h3>
  <strong>Container</strong>
</h3>

<p>Container by default have 90%</p>

```text
  <Container>
    <!-- Content -->
  </Container>
```

<p>Using the "full" props the container will have 100%</p>

```diff
!  <Container full>
    <!-- Content -->
  </Container>
```

<h3>
  <strong>Nav</strong>
</h3>

<h4>
  <strong>Example</strong>
</h4>

```text
  <Nav>

  </Nav>
```

<h3>
  <strong>Navbar</strong>
</h3>

<h4>
  <strong>Example</strong>
</h4>

```text
  <Navbar>

  </Navbar>
```

<h3>
  <strong>NavbarBrand</strong>
</h3>

<h4>
  <strong>Example</strong>
</h4>

```text
  <Navbar>
    <NavbarBrand href="">link</NavbarBrand>
  </Navbar>
```


## License

[MIT License](https://github.com/deividmfl/bebe-styled/blob/master/LICENSE)