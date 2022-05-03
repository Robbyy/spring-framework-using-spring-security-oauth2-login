Local Keycloak

admin/admin

standalone.bat -Djboss.http.port=8081

localhost:8081

Added the following VM flags

--add-opens=java.base/java.util=ALL-UNNAMED
--add-opens=java.base/java.lang=ALL-UNNAMED