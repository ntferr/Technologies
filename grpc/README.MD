# GO - GRPC

### Como gerar proto
<p>Primeiro gere o arquivo "input_name".proto, que irá ser uma definição dos dados que iram trafegar via GRPC.
Feito isso, basta gerar o arquivo proto "named_you_defined_for.proto".pb.go.</p>
<p>Execute os seguinte comando no seu terminal: 
protoc --go-grpc_out=. "named_you_defined_for.proto".proto</p>

### Output
![output](https://github.com/ntferr/images/blob/main/golang-grpc/grpc_output.png)
