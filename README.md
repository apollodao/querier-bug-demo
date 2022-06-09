# Querier Bug Demo

Minimal example showing that the Terra querier uses current time instead of block time for env.block.time.

Query it with {"get_time":{}} at previous block heights and it will not use the blocks timestamp for `env.block.time.seconds()` as it should.
