# holdout-npm-mixed

Repositorio sintético del conjunto de reserva (*hold-out*) del TFG *Análisis automatizado de vulnerabilidades en dependencias de software*. No contiene código, solo el manifiesto de dependencias.

No se usó para diseñar sca-gate. El ground truth (`ground_truth.yaml`) se escribió antes de ejecutar la herramienta sobre él.

| Dimensión | Paquete | Identificador |
|---|---|---|
| directa | node-fetch | CVE-2022-0235 |
| transitiva (request 2.88.2 fija tough-cookie ~2.5.0) | tough-cookie | CVE-2023-26136 |
| aviso retirado, CVE-2022-23529 rechazado | jsonwebtoken | GHSA-27h2-hvpr-p74q |
