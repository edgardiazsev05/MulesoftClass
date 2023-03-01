# ADR 001: Sizing: Message PER API

## Context

Es necesario medir la cantidad de mensajes que son procesados por la aplicación y conocer cuantos recursos son utilizados para reducir costos en recursos asignados.

## Decision

Medir cantidad de mensajes y/o procesamiento que tiene la aplicación

## Status

Propuesta

## Consequences

Con esta mediciones podemos conocer si la aplicación en realidad consume todos los recursos asignados, si en dado caso que no consuma todos los recursos es posible
disminuir los recursos asignados y ahorrar en costo.


## Related documents

https://github.com/pmerson/ADR-template

### References
- https://github.com/joelparkerhenderson/architecture-decision-record
- https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/examples/metrics-monitors-alerts/index.md
- https://github.com/pmerson/ADR-template
- https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/examples/timestamp-format/index.md
- https://cloud.google.com/architecture/architecture-decision-records
