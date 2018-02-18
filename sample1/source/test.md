# markdown

* [Title1](doc1.md)
* [Title2](doc2.md)

[API Reference](api_ref.md)

## だよー

mdがかけるよー

----

表は表現力の高いrstを
埋め込みで使えるよー

```eval_rst
=====  =====  =======
A      B      A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======
```

```eval_rst
.. mermaid::

   sequenceDiagram
      participant Alice
      participant Bob
      Alice->John: Hello John, how are you?
      loop Healthcheck
          John->John: Fight against hypochondria
      end
      Note right of John: Rational thoughts <br/>prevail...
      John-->Alice: Great!
      John->Bob: How about you?
      Bob-->John: Jolly good!
```
