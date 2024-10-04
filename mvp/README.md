# MVP VARIANT, PLAYGROUND, DIRTY VERSION

Playground to test each part before configure into modx plugin.


## Project requiremnts

- Vanila JS
- Use built-in modx (modx itself, and it plugins) methods to creating/updating/assigning any entity.
- Every new bulk upload, can be configured to filled up correctly.
- Each column of row can be splitted, into some times, and can be each splitted item assigned to specific tv or filter for minishop2 plugin.
- Must be as plugin inside modx.
- Cannot bulk uploading in main thread, must be in cron.


## Prototytpe

- Upload file in memory
- Get rows by chunks to prevent memory leak.
- allow split each column in as many times as needed.
- allow assign each splitted result into specific tv or page tv, or setup as minishop2 filter
- then port that split info with assigning to tvs into php in cron job, for next php uploading product.


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## TAGS

- Extensibility
- Configuration Management
- Flexible CSV Parsing
- Dynamic Field Mapping
- Customizable Splitting Rules
- MODX Plugin Development

## Workflow & Optimization 

- Workflow Optimization
- Data Processing
- Data Validation
- Data Transformation
- Batch Processing
- Performance:

## Performance Optimization
- Scalability
- Resource Management
- Memory Management
- Database Optimization