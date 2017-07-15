# Problem statement
gets an azure servicebus topic connection string

# Example usage

> note: in examples, VERSION represents a version of the azure.servicebus.topic.connectionstring.get pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/azure.servicebus.topic.connectionstring.get#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/azure.servicebus.topic.connectionstring.get#VERSION
```

## compose

```yaml
run:
  op:
    pkg: { ref: github.com/opspec-pkgs/azure.servicebus.topic.connectionstring.get#VERSION }
    inputs: 
      subscriptionId:
      loginId:
      loginSecret:
      loginTenantId:
      authRule:
      topic:
      namespace:
      resourceGroup:
      # begin optional args
      loginType:
      authRuleKey:
      # end optional args
    outputs:
      connectionString:
```

# Support

join us on [![Slack](https://opspec-slackin.herokuapp.com/badge.svg)](https://opspec-slackin.herokuapp.com/)
or [open an issue](https://github.com/opspec-pkgs/azure.servicebus.topic.connectionstring.get/issues)
