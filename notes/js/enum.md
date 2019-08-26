## Setup Enum
implement enum in javascript

#### sample code:

    'use strict';
    const obj = {
    prop: 42
    };

    Object.freeze(obj);

    obj.prop = 33;
    // Throws an error in strict mode

    console.log(obj.prop);
    // expected output: 42

refer: https://developer.mozilla.org/zh-TW/docs/Web/JavaScript/Reference/Global_Objects/Object/freeze

