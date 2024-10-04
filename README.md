# Import Products From Non Strict CSV for MODX

Idea is create plugin form modx (can be ported to any or none) to import product from non strict csv file, since job description was mention everytime is filled different, and cannot to be strict by any part of side. 

Each column of product row can be splitted into different ways and each result can be assigned to specific existed tv field or tv field of page, with opportunity of setup as filter parametr. Filter pipeline is asign create filer to category then fill can be filled up in product, this is the pipeline of product in modx with shop plugin "minishop2".


## Project requiremnts

- Vanila JS
- Use built-in modx (modx itself, and it plugins) methods to creating/updating/assigning any entity.
- Every new bulk upload, can be configured to filled up correctly.
- Each column of row can be splitted, into some times, and can be each splitted item assigned to specific tv or filter for minishop2 plugin.
- Must be as plugin inside modx.
- Cannot bulk uploading in main thread, must be in cron.


## Installation

Will be in feature


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