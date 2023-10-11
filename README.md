# Tinkoff ControlValueAccessor for contenteditable elements

[![⚙️ CI](https://github.com/taiga-family/angular-contenteditable-accessor/actions/workflows/ci.yml/badge.svg)](https://github.com/taiga-family/angular-contenteditable-accessor/actions/workflows/ci.yml)
[![npm version](https://img.shields.io/npm/v/@tinkoff/angular-contenteditable-accessor.svg)](https://www.npmjs.com/package/@tinkoff/angular-contenteditable-accessor)

> This accessor allows you to use Angular forms with contenteditable elements with ease. It has zero dependencies, other than Angular itself as peer and works with Angular 4+ in all modern browsers, including _Internet Explorer 11_.

## Install

```
$ npm install @tinkoff/angular-contenteditable-accessor
```

## Import

Simply import `ContenteditableValueAccessorModule` along with either Angular's form modules into your component's module

## How to use

Use with template and reactive forms like that:

    <div [(ngModel)]="model" contenteditable></div>

    <div [formControl]="control" contenteditable></div>

    <form [formGroup]="group">
      <div formControlName="control" contenteditable></div>
    </form>

## Demo

https://stackblitz.com/edit/angular2-contenteditable-value-accessor

## Maintain

See [MAINTAIN.md](MAINTAIN.md)
