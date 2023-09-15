[back to index](index.md)

# [Sonar Cloud rule java S112 - Define and throw a dedicated exception instead of using a generic one](https://sonarcloud.io/organizations/fugerit-org/rules?open=java%3AS112&rule_key=java%3AS112)

Has been handled in one of these ways : 
1. Set as Won't fix (with reasn 'This is a widespread api in many software modules, I do not want to break compatibility.')
2. java.lang.Exception removed in favor of org.fugerit.java.core.cfg.ConfigRuntimeException