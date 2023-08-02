ARG  FROMIMAGE=cp.icr.io/cp/appc/ace-server-prod:latest
FROM ${FROMIMAGE}

USER root

RUN microdnf update && microdnf clean all

USER 1001