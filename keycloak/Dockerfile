FROM jboss/keycloak:10.0.2

COPY token-validation/target/token-validation.jar /opt/jboss/keycloak/standalone/deployments/
RUN touch /opt/jboss/keycloak/standalone/deployments/token-validation.jar.dodeploy
