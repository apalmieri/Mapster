Need more speed? Let's compile with [FastExpressionCompiler](https://github.com/dadhi/FastExpressionCompiler).

Getting the package

     PM> Install-Package FastExpressionCompiler

Then add following code on start up

    TypeAdapterConfig.GlobalSettings.Compiler = exp => exp.CompileFast();

That's it. Now your code will enjoy more than 30% faster!