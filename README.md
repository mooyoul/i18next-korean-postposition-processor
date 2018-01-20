[![Build Status](https://travis-ci.org/Perlmint/i18next-korean-postposition-processor.svg?branch=master)](https://travis-ci.org/Perlmint/i18next-korean-postposition-processor)[![Coverage Status](https://coveralls.io/repos/github/Perlmint/i18next-korean-postposition-processor/badge.svg?branch=master)](https://coveralls.io/github/Perlmint/i18next-korean-postposition-processor?branch=master)[![dependencies Status](https://david-dm.org/perlmint/i18next-korean-postposition-processor/status.svg)](https://david-dm.org/perlmint/i18next-korean-postposition-processor)
# i18next-korean-postposition-processor

i18next post-processor for processing korean postposition - `을/를`, `이/가`, `은/는`, `으로/로`, `과/와`.

This processor can handle korean character or arabic number(without decimal mark).

## Setup

```javascript
import KoreanPostProcessor from 'i18next-korean-postposition-processor';

i18next.use(KoreanPostProcessor);
```

## Translation text
```
{{some_value}}[[를]] 수정했다.
```