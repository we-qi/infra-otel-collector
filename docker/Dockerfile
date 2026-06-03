FROM otel/opentelemetry-collector-contrib:0.102.0

COPY config/otel-collector.yaml /etc/otelcol-contrib/config.yaml

EXPOSE 4317 4318 8888 8889

CMD ["--config=/etc/otelcol-contrib/config.yaml"]
