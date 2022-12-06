# localunionparser
Probabilistic Parser for Local Parser Names

## Install
```bash
> pip install https://github.com/labordata/localunionparser/archive/refs/heads/main.zip
```

## To Use
```Python console
>>> import localunionparser
>>> localunionparser.parse('UNITE HERE 10')
[('UNITE', 'AffiliationAbbreviation'), ('HERE', 'AffiliationAbbreviation'), ('10', 'LocalIdentifier')]
>>> localunionparser.tag('UNITE HERE 10')
OrderedDict([('AffiliationAbbreviation', 'UNITE HERE'), ('LocalIdentifier', '10')])
```
