Detect Secrets that could be exposed from anywhere.

Block secrets from source code - ADO Advanced Security, [[Git Webhook]]
	7 out of 1K commits expose secrets.
	How do we find existing secrets?
Detect and remediate

Keys to secure:
	API Keys
	SSH Keys
	Certificates

[[Honeytokes]] - Embed in code to track who took secrets



[[CyberArk]]

Eliminate Creds where possible
MFA

Rotate Creds using automation - Secrets auto Rotation
1. Create new secret
	1. Test new secret
2. Swap new secret with existing one
3. Test to make sure nothing breaks
4. Clean up step for internal labeling
[[Zero Downtime Credential Rotation]]

Tools:
[[HashiCorp Vault]]
[[AKEYLESS]]
[[CyberArk]]
[[Doppler]]
[[gitLeaks]]

Further Reference:
[[The Cuckoo's Egg]] by Clifford Stoll

[[SPIFFE]] Secure Production Identity Framework for Everyone
	https://spiffe.io/book/
	https://youtu.be/4HHvEamsxjs?si=KZhaCL_51QKAMuG3](https://youtu.be/4HHvEamsxjs?si=KZhaCL_51QKAMuG3)
[[SPIRE]]  Toolchain of APIs to establish trust between systems

Automation Tool Examples

[https://github.com/aws-samples/aws-secrets-manager-rotation-lambdas/blob/master/SecretsManagerRotationTemplate/lambda_function.py](https://github.com/aws-samples/aws-secrets-manager-rotation-lambdas/blob/master/SecretsManagerRotationTemplate/lambda_function.py)











