# protobuff

#### To build a .go file from .proto run the following command
* protc -I=$SRC_DIR --go_out=$DST_DIR $SRC_DIR/addressbook.proto 
##### example from this project
* protoc -I=proto --go_out=proto proto/scalar-type.proto
