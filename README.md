# React Portal Overlay

[![NPM](https://img.shields.io/npm/v/@peacechen/react-portal-overlay)](https://www.npmjs.com/package/@peacechen/react-portal-overlay) [![License](https://img.shields.io/npm/l/react-portal-overlay)](https://github.com/seaneking/react-portal-overlay/blob/master/LICENSE.md)

This is a fork of https://madeleineostoja.github.io/react-portal-overlay and published as a separate package on [npmjs.com](https://www.npmjs.com/package/@peacechen/react-portal-overlay) to unlock the peer dependencies.

A lightweight and performant fullscreen overlay component using React portals to render anywhere you need them to

## Installation

```sh
npm i @peacechen/react-portal-overlay
```

## Usage

See the [API Docs](https://madeleineostoja.github.io/react-portal-overlay/) for a full overview of props and options.

```js
import React, { useState } from 'react';
import { Overlay } from '@peacechen/react-portal-overlay';

export default () => {
  const [open, setOpen] = useState(false);

  return (
    <Overlay open={open} onClose={() => setOpen(false)}>
      <h1>My overlay</h1>
    </Overlay>
  );
};
```
