# Plan de pagos – venta del auto

Página pública (GitHub Pages): el comprador ve qué está pagado y qué falta.

## Modo vendedor (desde la misma página)

Tocá el 🔒 al lado del título, poné el PIN y tildá los pagos. La primera vez en cada
celular/compu pide una llave de GitHub (fine-grained token, solo este repo,
Contents: Read and write); queda guardada solo en ese navegador.

## Cómo marcar un pago a mano (alternativa)

1. Abrí `pagos.json` en GitHub y tocá el lápiz (editar).
2. En el pago cobrado poné la fecha en formato `AAAA-MM-DD`, por ejemplo:
   `"entrega": "2026-11-17",` o `"1": "2026-11-25",`
3. Guardá con **Commit changes**. En 1–2 minutos la página se actualiza.

Para desmarcar, dejá la fecha vacía: `"1": ""`.

| Pago | Vence | Monto |
|---|---|---|
| Entrega (resto) | 17 nov 2026 | $300.000 |
| Cuotas 1–9 | del 20 al 30 de cada mes, nov 2026 a jul 2027 | $250.000 c/u |
| Cuota 10 | 20 al 30 ago 2027 | $150.000 |

Total $3.000.000 (entrega ya recibida: $300.000).
