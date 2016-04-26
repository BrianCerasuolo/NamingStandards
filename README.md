# Naming Standards

## C#

The general rule we follow is "use ReSharper defaults"

1. We use `_camelCase` for internal and private fields and use `readonly` where possible.
2. Avoid more than one empty line at any time. For example, do not have two blank lines between members of a type.
3. We use PascalCasing to name all our constant local variables and fields.
4. Variables suffixed with Id should always use Id and never ID
5. Acroynyms should use PascalCase, ignoring the acroynym.
 ```C#
    // bad
    public string CPPQuote {get;set;}
    public int ISMREtailRep {get;set;}
    public string HTTPPath {get;set;}

    // good
    public string CppQuote {get;set;}
    public int IsmREtailRep {get;set;}
    public string HttpPath {get;set;}
    ```

## Javascript