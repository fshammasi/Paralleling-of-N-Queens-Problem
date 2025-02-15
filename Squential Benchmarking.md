## Benchmarking Results for all code without modifications

| Board Size (N) | 1st Trial (seconds)      | 2nd Trial (seconds)      |
|----------------|--------------------------|--------------------------|
| 8              | 0.0460612                | 0.0443975                | 
| 9              | 0.141671                 | 0.0026572                | 
| 10             | 0.411308                 | 0.0116965                | 
| 11             | 1.29722                  | 0.0695131                | 
| 12             | 6.96078                  | 0.35401                  | 
| 13             | 43.4933                  | 2.30633                  | 
| 14             | 287  (4.7833 min)        | 14.1735                  | 
| 15             | 2502.04                  | -                        | 
| 16             | 724.58                   | -                        |



## Benchmarking Results for all the code after deleting print statements and 

| Board Size (N) | Number of Solutions | 1st Trial (seconds)      | 2nd Trial (seconds)      |
|----------------|---------------------|--------------------------|--------------------------|
| 8              | 92                  | 0.0005402                | 0.0007                   | 
| 9              | 352                 | 0.0027062                | 0.0026572                | 
| 10             | 724                 | 0.011859                 | 0.0116965                | 
| 11             | 2680                | 0.0564891                | 0.0695131                | 
| 12             | 14200               | 0.305196                 | 0.35401                  | 
| 13             | 73712               | 2.26089                  | 2.30633                  | 
| 14             | 365596              | 12.0875                  | 14.1735                  | 
| 15             | 2279184             | 99.0735                  | 99.23                    | 
| 16             | 14772512            | 724.58                   | 724.594                  |
