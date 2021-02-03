# JSON_handling


- Handling of JSON File : Json to csv converter.
      
      >>> d = {
          'a': [1,2,3],
           'b': ['alex', 'bert', 'cam'],
           'c': [0],
           'd': list(range(10))
      }
      >>> j = json.dumps(d)
      >>> j
      {"a": [1, 2, 3], "b": ["alex", "bert", "cam"], "c": [0], "d": [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]}
      df = JSON_to_str(j)
      >>> df

 ![](/images/df.png)
