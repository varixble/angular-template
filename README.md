<p align="center">
  <a href="http://varixble.com">
    <img src="http://varixble.com/assets/img/logo_black_w_32@2x.png" width="192px" height="192px"/>
  </a>
</p>

<h1 align="center">
    Proyecto Angular 7
</h1>

<p align="center">
    Architecture example of Angular 7, RouterRedux, Router  😊
  <br />
  <a href="#table-of-contents"><strong>Explore the docs</strong></a>
  <br />
</p>

## Table of Contents

* [🛠️ Environment setup](#-environment-setup)
* [🤔 Architecture](#-architecture)

## ️️️️️🛠️ Environment setup

1. Install Node `https://nodejs.org/` y Angular Cli: `https://cli.angular.io/` 
2. Clone this project: `git clone git@github.com:varixble/angular-template.git`
3. Move to the project folder: `cd angular-template`
4. Install dependencies: `npm install
5. Execute: `ng s --o`
6. Go to: `http://localhost:4200`

## 🤔 Architecture

This repository follow: 
````scala
src
|-- App 
|   |-- Admin 
|   |   `-- Main
|   |-- Auth
|   |   `-- Login
|   |-- Core
|   |   `-- Store
|   |       |-- LocalStorage
|   |       |-- Models
|   |       `-- State
|   `-- Shared
|-- Assets
|   |-- Fonts
|   |-- Images
|   `-- Scss
`-- Environments
````