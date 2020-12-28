# @riski-react-ui/date-picker

> Datepicker React Component (build with Typescript) based Material-UI

[![NPM](https://img.shields.io/npm/v/@riski-react-ui/date-picker.svg)](https://www.npmjs.com/package/@riski-react-ui/date-picker) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)![npm bundle size]

---

## Install

```bash
npm install --save @riski-react-ui/date-picker
```

## Usage

```jsx
import React from 'react';

import DatePicker from '@riski-react-ui/date-picker';

const onDatePickerDateChange = () => {};

<DatePicker
  id="search-date"
  datePickerChangeHandler={onDatePickerDateChange}
  name="SeacrhDate"
  label="Дата поиска"
  value="2020-12-28"
  maxDate="2021-12-31"
  minDate="2020-12-01"
  minDateMessage="Дата меньше допустимой"
  maxDateMessage="Дата больше допустимой"
/>
```

## Props

## License

MIT © [DenisBykov](https://github.com/BykovDenis)
