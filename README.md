# api-pipeline

an example OpenAPI specification repository that included a delivery pipeline including the following:

- "build" by composing multiple specifications into one.
- .lint specification based on generic and specific rules
- Non-breaking change verification.
- Difference/change report
- Semantic versioning (based on change type: breaking, minor, info)
- package
- release (GitHub, NPM, etc.)

Future considerations:

- Build SDK
- Acceptance testing 
- Delivery (over and above release, e.g. host)

## References

https://www.npmjs.com/package/openapi-diff

## From scratch on Windows

```bat
choco upgrade nodejs
```

## packages

npm install openapi-diff --save-dev
