
# CABECERA H1
## CABECERA H2
### CABECERA H3
#### Cabecera H4
##### Cabecera H5
##### Cabecera H6

Underline1
----------

Underline2
==========

Haciendo texto de prueba para mi README en mi repositorio de GIT HUB. Este readme pertene a un repositorio de aprendizaje. Haciendo underline con =
==================================================================================
# **Formatos de Emphasis**
- formato *italica* de la primera forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** primera forma.
- formato __bold o strong__ primera forma.
- formato ~~tachado~~.

Aqui podemos usar formato *italica*, pero tambien en la misma linea podemos poner formato **strong** y un ~tachado~.

# Listas
1. Esto es un item en una lista ordenada.
2. Esto es un item en una lista ordenada.
3. Esto es un item en una lista ordenada.
- Esto es un item en lista desordenada
- Esto es un item en lista desordenada
- Esto es un item en lista desordenada

<!-- Esto es un comentario en html -->

# Links
- [Esto es un link en MD](http://wwww.google.es)
- [Esto es un link a index](index.html)

# Imagenes
![Logo GitHub](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcStJ661_VwO4iG6mzSlGKrrM3SD7L8iPCl7Zg&usqp=CAU)

# Code Snippets
Codigo en JSON.
```JSON
[
    [
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
]
```
Codigo en PHP.
```PHP
[
    require_once 'Zend/Uri/Http.php';

namespace Location\Web;

interface Factory
{
    static function _factory();
}

abstract class URI extends BaseURI implements Factory
{
    abstract function test();

    public static $st1 = 1;
    const ME = "Yo";
    var $list = NULL;
    private $var;

    /**
     * Returns a URI
     *
     * @return URI
     */
    static public function _factory($stats = array(), $uri = 'http')
    {
        echo __METHOD__;
        $uri = explode(':', $uri, 0b10);
        $schemeSpecific = isset($uri[1]) ? $uri[1] : '';
        $desc = 'Multi
line description';

        // Security check
        if (!ctype_alnum($scheme)) {
            throw new Zend_Uri_Exception('Illegal scheme');
        }

        $this->var = 0 - self::$st;
        $this->list = list(Array("1"=> 2, 2=>self::ME, 3 => \Location\Web\URI::class));

        return [
            'uri'   => $uri,
            'value' => null,
        ];
    }
}

echo URI::ME . URI::$st1;

__halt_compiler () ; datahere
datahere
datahere */
datahere
]
```
