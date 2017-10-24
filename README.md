# metadata

A Java library that manages SPARQL Builder Metadata (SBM; http://www.sparqlbuilder.org/doc/) that describes a profile of SPARQL Endpoint for SPARQL Builder (http://www.sparqlbuilder.org).
This library includes a crawler that obtains the SBM by querying a set of SPARQL queries.

# Usage:
For SPARQL endpoints;
See original repository https://github.com/sparqlbuilder/metadata

For local Virtuoso;
1. Unpack dist.tar.gz
2. % cd dist
3. % java -jar -Xmx1000m -Xms1000m -XX:-UseGCOverheadLimit VirtMetadata.jar -virt -ac endpointURL sbm sbm
4. enter virtuoso jdbc port (to use default setting "jdbc:virtuoso://localhost:1111", just push return.) when asked.
5. enter user id for virtuoso or just push return (default "dba") when asked
6. enter password or just push return (default "dba") when asked
7. wait for a while :)
8. you can find sbm files in the folder "sbm"
