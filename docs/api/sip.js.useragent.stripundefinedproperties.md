<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [sip.js](./sip.js.md) &gt; [UserAgent](./sip.js.useragent.md) &gt; [stripUndefinedProperties](./sip.js.useragent.stripundefinedproperties.md)

## UserAgent.stripUndefinedProperties() method

Strip properties with undefined values from options. This is a work around while waiting for missing vs undefined to be addressed (or not)... https://github.com/Microsoft/TypeScript/issues/13195

<b>Signature:</b>

```typescript
protected static stripUndefinedProperties(options: Partial<UserAgentOptions>): Partial<UserAgentOptions>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  options | <code>Partial&lt;UserAgentOptions&gt;</code> | Options to reduce |

<b>Returns:</b>

`Partial<UserAgentOptions>`
