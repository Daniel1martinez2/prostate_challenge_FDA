| Campo                         | Descripción                                                          |
|:------------------------------|:---------------------------------------------------------------------|
| AGRUPACION_DIASTOLICA         | Resultado Ultima Toma Tension Sistolica                              |
| AGRUPACION_SISTOLICA          | Resultado Ultima Toma Tension Diastolica                             |
| CANCER_MAMA_FAMILIAR          | Tienen Antecedentes De Cancer_Mama_Familiar                          |
| CANCER_OTRO_SITIO             | El Usuario Tiene Cancer_Otro_Sitio Fuente Antecedentes               |
| CANCER_OTRO_SITIO_FAMILIAR    | Tienen Antecedentes De Cancer_Otro_Sitio_Familiar                    |
| Cant_Fliar_CP                 | Tiene Familiar con Cancer de Prostata?                               |
| Cant_Fliar_riesgos            | Cantidad de riesgos del grupo Familiar                               |
| Cant_gr_flia                  | Cantidad de personas en el grupo familiar                            |
| Cant_riesgos_flia_mean        | Cantidad promedio de riesgos en familia                              |
| cantidad_serv_flia            | Cantidad de Servicios prestados a la familia en el ultimo semestre   |
| CANTIDAD_SERVICIOS            | Cantidad de Servicios prestados al usuario en el ultimo semestre     |
| CEREBRAL                      | Ha presentado enfermedad cerebral?                                   |
| CEREBRAL_FAMILIAR             | Tienen Antecedentes De Cerebral_Familiar                             |
| conteo_dx_diferentes          | Cuantos Diagnosticos ha presentado en el ultimo semestre             |
| CORONARIOS                    | Ha presentado enfermedad coronaria?                                  |
| CORONARIOS_FAMILIAR           | Tienen Antecedentes De Coronarios Familiar                           |
| DIABETES                      | Ha presentado Diabetes?                                              |
| DIABETES_FAMILIAR             | Tienen Antecedentes De Diabetes Familiar                             |
| EDAD                          | Edad del Usuario                                                     |
| ENFERMEDAD_RENAL              | Ha presentado Enfermedad Renal?                                      |
| ENFERMEDAD_RENAL_FAMILIAR     | Tienen Antecedentes De Enfermedad Renal Familiar                     |
| ESTADO_CIVI                   | Estado Civil del Usuario                                             |
| estrato                       | Estrato sociodemografico del usuario                                 |
| GENERO                        | Genero Usuario                                                       |
| GRUPO_ETAREO                  | Grupo Etareo                                                         |
| HIPERTENSION                  | Ha presentado HTA?                                                   |
| HIPERTENSION_FAMILIAR         | Tienen Antecedentes De HTA Familiar                                  |
| IMC                           | Indice de masa corporal                                              |
| Intercepto                    | Intercepto del costo del ultimo semestre                             |
| Intercepto_flia               | Incercepto del costo familiar del ultimo semetre                     |
| MEDICAMENTOS                  | Cantidad de medicamentos usados en el ultimo semestre                |
| MEDICINA ESPECIALIZADA        | Cantidad de servicios de medicina especializada en el ultimo semtres |
| MEDICINA GENERAL              | Cantidad de servicios de medicina general en el ultimo semtres       |
| min_Tiempo_CP_Fliar           | Tiempo desde la marca del CA de Prostata Familiar                    |
| OTROS_ANTECEDENTES_VASCULARES | Tienen Antecedentes De enfermedad vascular?                          |
| parentesco                    | Parentezco con el cotizante                                          |
| Pendiente                     | Pendiente del costo en el ultimo semestre                            |
| Pendiente_flia                | Pendiente del costo familiar en el ultimo semestre                   |
| PERDIDA_DE_PESO               | Peso perdido/ganado en el ultimo año                                 |
| PROGRAMA                      | Programa actual del usuario                                          |
| Promedio_costo                | Promedio del costo en el ultimo semestre                             |
| Promedio_costo_flia           | Promedio del costo familiar en el ultimo semestre                    |
| psa_max_gr_flia               | Resultado PSA Maximo del grupo familiar                              |
| psa_min_gr_flia               | Resultado PSA Minimo del grupo familiar                              |
| RIESGOS                       | cantidad de riesgos del usuario                                      |
| Target                        | Resultado numerico del PSA                                           |
| Target_clase                  | Resultado anormal o normal del PSA                                   |
| TIEMPO_AFILIACION             | Tiempo de afiliación del usuario                                     |
| TIEMPO_ULTIMA_CITA            | Tiempo desde la ultima cita del usuario                              |

---

- Entendimiento y preparación de datos:
   - Análisis del baseline (0.2 puntos)
   - Análisis de missing values (0.2 puntos)
   - Análisis de outliers (0.2 puntos)
   - Imputación de valores (0.4 puntos)
- Feature Engineering:
  - Tratamiento de variables categóricas (0.2 puntos)
  - Uso de PCA (0.4 puntos)
  - Selección de variables (0.4 puntos)
- Calibración y selección de modelo
  - Custom Transformers (0.4)
  - Uso de Optimización bayesiana (0.6 puntos)
  - SVC con diferentes kernels (0.8 puntos)
  - Redes neuronales densas poco profundas (1 punto)
  - Escogencia del flujo final (0.2 puntos)