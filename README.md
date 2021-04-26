# sos-xeus-cling
## SoS extension for C++. Developed independently from original SoS team. Please refer to [SoS Homepage](http://vatlab.github.io/SoS/) for details.

This language extension to SoS allows to use C++ with xeus-cling Jupyter kernel (https://github.com/QuantStack/xeus-cling) and exchange variables with other languages in Polyglot environment

**NOTE: early stage development, not ready for use**

### Supported variable types for transfer

#### From C++ to SoS (`%put` magic):

| Source: C++ type                             | Destination: SoS (Python) type |
|----------------------------------------------|--------------------------------|
| `int` `short int` `long int` `long long int` | `int`                          |
| `float` `double`                             | `float`                        |
|                                              |                                |
|                                              |                                |
|                                              |                                |
|                                              |                                |
|                                              |                                |
|                                              |                                |
|                                              |                                |
|                                              |                                |
|                                              |                                |
|                                              |                                |
|                                              |                                |
|                                              |                                |

#### From SoS to C++ (`%get` magic):
