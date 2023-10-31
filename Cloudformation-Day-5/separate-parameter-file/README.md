# How to create a stack
aws cloudformation create-stack --stack-name dev-network-infra-pf --template-body file://network_infra.yaml --parameters file://dev-parameter-file.json
# How to delete a stack
#The following delete-stack example deletes the specified stack.
aws cloudformation delete-stack \
    --stack-name my-stack