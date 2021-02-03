## README


| Command | Description / Examples |
| --- | --- |
| `DUMP` | Dump anything |
| | `DUMP "Some objects: ", s:my_obja, s:other_obj` |
| | `DUMP s:foo` |
| `LLOG` | Log with file:line and call information |
| | `LLOG "The ID=" . string(s:foo.id)` |
| `LLOG2` | |
| `LLOG3` | |
| `LLOG4` | same as `LLOG`, but as each command can be silenced one can turn logging on / off for selected information. |
| `LOG` | Plain logging. Does not log filename, linenumber, function, ... |
| | `LOG "Hello"` |
| `QLOG` | Quoted plain logging. Same as `LOG` but output is wrapped in quotes. |
| | `QLOG "Hello"` |
| `EXLOG` | Log result of executing |
| | `EXLOG reltime()` |
| | `EXLOG :messages` |
| | `EXLOG :verbose function` |

---









* `DUMP`  : Dump anything
    * `DUMP "Some objects: ", s:my_obja, s:other_obj`
    * `DUMP s:foo`
* `LLOG`  : Log with time, file and line information
    * `LLOG "The ID=" . string(s:foo.id)`
* `LLOG2`, `LLOG3` and `LLOG4` : same as `LLOG`, but as each command can be silenced one can turn logging on / off for selected information.
* `LOG`   : Plain logging. Does not log filename, linenumber, function, ...
    * `LOG "Hello"`
* `QLOG`  : Quoted plain logging. Same as `LOG` but output is wrapped in quotes.
    * `QLOG "Hello"`
* `EXLOG` : Log result of executing
    * `EXLOG reltime()`
    * `EXLOG :messages`
    * `EXLOG :verbose function`



