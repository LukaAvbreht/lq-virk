# Introduction

[VIRK.dk](https://indberet.virk.dk/) contains (among other things) financial statements of Danish companies in a machine-readable form
an accessible via a web service.
This little library makes it easier to fetch and extract this data in a tabular form, e.g. as a pandas data frame.
The library can be used either as a standard python module or via [Liquer](https://orest-d.github.io/liquer/) framework,
which provides additional functionality like caching and allows to expose the functionality as a web service (proxy).
Please consult [Liquer](https://orest-d.github.io/liquer/) page for more info.

# Install

```
git clone https://github.com/orest-d/lq-virk.git
cd lq-virk
pip3 install -r requirements.txt
```

# Demo

Demo proxy is installed on http://orest3d.pythonanywhere.com/liquer/q/

Try e.g. [http://orest3d.pythonanywhere.com/liquer/q/ns-virk/register/register.html]