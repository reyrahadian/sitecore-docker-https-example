#escape=`
ARG BASE_IMAGE

FROM $BASE_IMAGE

COPY --from=traefik:v2.1.3-windowsservercore-1809 /traefik.exe /traefik/traefik.exe

ENTRYPOINT ["C:\\traefik\\traefik.exe"]
