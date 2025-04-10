# Swagger to RDF Converter

## Overview
The `swaggertordf.py` script converts Swagger/OpenAPI JSON files into RDF/XML ontology format. This enhanced script captures the full structure of the API, including endpoints, parameters, request bodies, responses, and security schemes, to support potential roundtrip conversions.

## Usage
To run the script, use the following command:
```bash
python3 swaggertordf.py <input_swagger.json> <output_rdf.xml>
```

### Example
To convert a Swagger/OpenAPI JSON file located at `/home/gaian/Downloads/api-docs-holacracy.json` to RDF/XML format, use the following command:

```bash
python3 swaggertordf.py /home/gaian/Downloads/api-docs-holacracy.json /home/gaian/Downloads/pientityservices_latest1046.rdf
```

## Input
- **Input File**: A Swagger/OpenAPI JSON file that describes the API.

## Output
- **Output File**: An RDF/XML file that represents the API ontology.


## Contact
For any inquiries, please contact [Sai Ravi Chandra](mailto: gangavarapu.s@mobiusdtaas.ai).
