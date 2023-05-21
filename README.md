# KUTTL Test

## Description
The test suite for this Kyverno policy validates the policy's functionality and effectiveness. It covers multiple scenarios to ensure proper enforcement and accurate labeling of Kubernetes resources. The test suite employs a combination of configuration files and scripts to assert the desired behavior, guaranteeing the policy's accuracy and preventing unintended modifications.

## Running the test

```
kubectl kuttl test ./tests/
```

## Output

Should get the following output at the completion of the test case:
![image](https://github.com/Ashwin901/kyverno-policy-kuttl-test/assets/56069189/d023888d-4d88-4e82-9dc2-ebd127d22254)
