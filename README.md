## Listado de Servicios o 1 servicio
Response:
```json
{
    "current_page": 1,
    "data": [
        {
            "id": 6777,
            "declared_value": "435345.00",
            "round_trip": false,
            "programmed": true,
            "kms_amount": "0.00",
            "approx_duration": "4 horas",
            "total_price": "67850.00",
            "base_price": "67850.00",
            "date_time": "2020-02-28 14:00:00",
            "invoice_id": null,
            "coupon_id": null,
            "agree_terms": true,
            "created_at": "2020-02-12 21:57:44",
            "petition_id": 325,
            "line": "express",
            "stops": [
                {
                    "id": 14917,
                    "latitude": "4.6861583000",
                    "longitude": "-74.1216670000",
                    "address": "Tv. 93 ## 51 - 98, Bogotá, Colombia",
                    "order": 1,
                    "description": "sdf",
                    "worker_observation": null,
                    "service_id": 6777
                }
            ],
            "city": {
                "id": 1,
                "name": "Bogotá",
                "code": 1,
                "latitude": "4.6261162000",
                "longitude": "-74.0826451000",
                "zoom": 17,
                "country_state_id": 11,
                "radius": null,
                "periphery_distance": 3
            },
            "states": [
                {
                    "name": "Asignado",
                    "description": "",
                    "service_state_name": "Asignado",
                    "service_id": 6754,
                    "service_state_id": 1
                },
                {
                    "name": "Finalizado",
                    "description": "",
                    "service_state_name": "Finalizado",
                    "service_id": 6754,
                    "service_state_id": 3
                }
            ],
            "payment_method": {
                "id": 3,
                "name": "Tarjeta"
            },
            "service_type": {
                "id": 2,
                "name": "Moto",
                "description": ""
            },
            "modality": {
                "id": 1,
                "name": "Medio Día"
            },
            "user": {
                "id": 1426,
                "first_name": "Enyor",
                "last_name": "Piña",
                "email": "enyor888@gmail.com",
                "mobile_phone": 3123350281,
                "image": null,
                "address": "Tv 93 51 98",
                "gender": null,
                "city_id": 1,
                "nid_id": 2,
                "active": true,
                "created_at": "2019-10-18 13:55:43",
                "nid": 966587,
                "fullName": "Enyor Piña",
                "branch_officies": [{
                        "id": 422,
                        "name": "",
                        "company_id": 444,
                        "branch_office_id": 422,
                        "company": {
                            "id": 444,
                            "nid_id": 4,
                            "nid": 9586899,
                            "company_name": "Cliente - Emp",
                            "legal_name": "Cliente - Emp",
                            "contact_role": "rge",
                            "billing_address": "av siemre viviv222aaa",
                            "agree_terms": false,
                            "billing_period": null
                        }
                    }]
            },
            "worker": {
                "id": 88,
                "license": "E12332S5",
                "category_license": "A1",
                "image": null,
                "user_id": 115,
                "active": true,
                "device_app_version": "2014",
                "store_app_version": "2016",
                "assignments": 2,
                "capacity": 10,
                "license_expiration": null,
                "user": {
                    "id": 115,
                    "first_name": "Cristian",
                    "last_name": "Cruz Express",
                    "email": "cargarappsquick@gmail.com",
                    "mobile_phone": 1234567892,
                    "image": null,
                    "address": "Tv 93 51 98",
                    "gender": null,
                    "city_id": 1,
                    "nid_id": 1,
                    "active": true,
                    "created_at": "2019-07-02 17:54:48",
                    "nid": 1016082672,
                    "fullName": "Cristian Cruz Express"
                },
                "vehicles": [
                    {
                        "id": 89,
                        "brand": "Chevrolet",
                        "model": "Astra",
                        "car_plate": "AA946WW",
                        "insurance_number": "security",
                        "insurance": "provenir",
                        "image": null,
                        "service_type_id": 1,
                        "worker_id": 88,
                        "vehicle_brand_id": null,
                        "insurance_company_id": null,
                        "insurance_expiration": null,
                        "property_card_number": null,
                        "property_card_expedition": null,
                        "technicianmechanic_number": null,
                        "technicianmechanic_expiration": null,
                        "owner": false,
                        "vehicles_owner_id": null
                    },
                    {
                        "id": 168,
                        "brand": "Marca Quick",
                        "model": "2020",
                        "car_plate": "Qu123Z",
                        "insurance_number": "Poliza22 Quick",
                        "insurance": "Seguro Quick",
                        "image": null,
                        "service_type_id": 2,
                        "worker_id": 88,
                        "vehicle_brand_id": null,
                        "insurance_company_id": null,
                        "insurance_expiration": null,
                        "property_card_number": null,
                        "property_card_expedition": null,
                        "technicianmechanic_number": null,
                        "technicianmechanic_expiration": null,
                        "owner": false,
                        "vehicles_owner_id": null
                    },
                    {
                        "id": 87,
                        "brand": "DISCOVERY 100",
                        "model": "2019",
                        "car_plate": "XLZ-59E",
                        "insurance_number": "123456789",
                        "insurance": "MAPREF",
                        "image": null,
                        "service_type_id": 2,
                        "worker_id": 88,
                        "vehicle_brand_id": null,
                        "insurance_company_id": null,
                        "insurance_expiration": null,
                        "property_card_number": null,
                        "property_card_expedition": null,
                        "technicianmechanic_number": null,
                        "technicianmechanic_expiration": null,
                        "owner": false,
                        "vehicles_owner_id": null
                    }
                ]
            }        
        }
      ],
    "first_page_url": "https://api.quickapp.dev/express/services?page=1",
    "from": 1,
    "last_page": 1,
    "last_page_url": "https://api.quickapp.dev/express/services?page=1",
    "next_page_url": null,
    "path": "https://api.quickapp.dev/express/services",
    "per_page": 20,
    "prev_page_url": null,
    "to": 1,
    "total": 1
}
```
## Detalle de Servicio
Response:

```json
{
    "id": 6777,
    "stops": [
        {
            "id": 21,
            "stop_states": [],
            "name": "Stop",
            "latitude": "4.6258655000000000",
            "longitude": "-74.0703659999999800",
            "order": 0,
            "description": "asd",
            "worker_observation": "",
            "address": "Cl. 6A ##15-56, Bogotá, Colombia",
            "city": null,
            "service_id": 11
        },
        {
            "id": 22,
            "stop_states": [],
            "name": "Stop",
            "latitude": "4.5949985999999990",
            "longitude": "-74.0829866000000300",
            "order": 1,
            "description": "asda",
            "worker_observation": "",
            "address": "Cl. 5 #1145, Bogotá, Colombia",
            "city": null,
            "service_id": 11
        }
    ],
    "payment_method": {
        "id": 3,
        "name": "Tarjeta"
    },
    "service_type": {
        "id": 1,
        "name": "Runer Express"
    },
    "city": {
        "id": 1,
        "name": "Bogota"
    },
    "modality": {
        "id": 3,
        "name": "Vuelta"
    },
    "states": [
        {
            "id": 16,
            "service_state_name": "En Espera",
            "service_state_id": 1,
            "reason_description": null,
            "mishap_description": null,
            "mishap_type": null,
            "reason_type": null
        },
        {
            "id": 24,
            "service_state_name": "Asignado",
            "service_state_id": 2,
            "reason_description": null,
            "mishap_description": null,
            "service_state_type": 2,
            "mishap_type": null,
            "reason_type": null
        }
    ],
    "recharges": [
        {
            "id": 6,
            "value": "950.0000",
            "included_quantity": "3.0000",
			"quantity" : 5,
            "base_price_id": 18,
            "user": null,
            "recharge_value": 1900.0,
            "measure_units": {
                "id": 6,
                "name": "Cancelacion",
                "description": " "
            }
        }
    ],
    "worker": {
        "id": 1,
        "user": {
            "first_name": "arnol",
            "last_name": "caidecod",
            "mobile_phone": "193344525",
            "email": "worker2@gmail.com",
            "nid": "99872501",
            "nids_id": "1"
        }
    },
    "gain": null,
    "company": null,
    "user": {
        "first_name": "jose",
        "last_name": "salas",
        "mobile_phone": "3222408847",
        "email": "jose.salas@quick.com.co",
        "nid": "777777",
        "nids_id": "1"
    },
    "worker_vehicle": [
        {
            "id": 1,
            "brand": null,
            "model": "TY",
            "car_plate": "MM2-075",
            "image": "wdnw"
        }
    ],
    "discount": null,
    "declared_value": "3000.00",
    "round_trip": false,
    "programmed": false,
    "kms_amount": 6,
    "approx_duration": 18,
    "total_price": "9300.00",
    "base_price": "6150.00",
    "date_time": "2019-11-20T10:53:00",
    "invoice": "",
    "agree_terms": true,
    "massive": false,
    "active": true,
    "created_at": "2019-11-20T10:53:02.853307",
    "coupon": null,
    "history": 28
}

```

## Listado Worker
Response:
```json
{
                "id": 88,
                "license": "E12332S5",
                "category_license": "A1",
                "image": null,
                "user_id": 115,
                "active": true,
                "device_app_version": "2014",
                "store_app_version": "2016",
                "assignments": 2,
                "capacity": 10,
                "license_expiration": null,
                "users": {
                    "id": 115,
                    "first_name": "Cristian",
                    "last_name": "Cruz Express",
                    "email": "cargarappsquick@gmail.com",
                    "mobile_phone": 1234567892,
                    "image": null,
                    "address": "Tv 93 51 98",
                    "gender": null,
                    "city_id": 1,
                    "nid_id": 1,
                    "active": true,
                    "created_at": "2019-07-02 17:54:48",
                    "nid": 1016082672,
                    "fullName": "Cristian Cruz Express"
                },
                "vehicles": [
                    {
                        "id": 89,
                        "brand": "Chevrolet",
                        "model": "Astra",
                        "car_plate": "AA946WW",
                        "insurance_number": "security",
                        "insurance": "provenir",
                        "image": null,
                        "service_type_id": 1,
                        "worker_id": 88,
                        "vehicle_brand_id": null,
                        "insurance_company_id": null,
                        "insurance_expiration": null,
                        "property_card_number": null,
                        "property_card_expedition": null,
                        "technicianmechanic_number": null,
                        "technicianmechanic_expiration": null,
                        "owner": false,
                        "vehicles_owner_id": null
                    },
                    {
                        "id": 168,
                        "brand": "Marca Quick",
                        "model": "2020",
                        "car_plate": "Qu123Z",
                        "insurance_number": "Poliza22 Quick",
                        "insurance": "Seguro Quick",
                        "image": null,
                        "service_type_id": 2,
                        "worker_id": 88,
                        "vehicle_brand_id": null,
                        "insurance_company_id": null,
                        "insurance_expiration": null,
                        "property_card_number": null,
                        "property_card_expedition": null,
                        "technicianmechanic_number": null,
                        "technicianmechanic_expiration": null,
                        "owner": false,
                        "vehicles_owner_id": null
                    },
                    {
                        "id": 87,
                        "brand": "DISCOVERY 100",
                        "model": "2019",
                        "car_plate": "XLZ-59E",
                        "insurance_number": "123456789",
                        "insurance": "MAPREF",
                        "image": null,
                        "service_type_id": 2,
                        "worker_id": 88,
                        "vehicle_brand_id": null,
                        "insurance_company_id": null,
                        "insurance_expiration": null,
                        "property_card_number": null,
                        "property_card_expedition": null,
                        "technicianmechanic_number": null,
                        "technicianmechanic_expiration": null,
                        "owner": false,
                        "vehicles_owner_id": null
                    }
                ]
            }
```

## Calculate
Response: 
```json
{
    "price": 6500,
    "basePrice": "6500.00",
    "kms_amount": 3,
    "approx_duration": 373,
    "recharges": [
        {
            "id": 6,
            "value": "950.0000",
            "included_quantity": "3.0000",
			"quantity" : 5,
            "measure_unit_id": 1,
            "base_price_id": 18,
            "user": null,
            "recharge_value": 5500.0
        },
        {
            "id": 12,
            "value": "2700.0000",
            "included_quantity": "2.0000",
			"quantity" : 5,
            "measure_unit_id": 4,
            "base_price_id": 18,
            "user": null,
            "recharge_value": 5500.0
        },
        {
            "id": 36,
            "value": "0.0200",
            "included_quantity": "500000.0000",
			"quantity" : 5,
            "measure_unit_id": 5,
            "base_price_id": 18,
            "user": null,
            "recharge_value": 5500.0
        },
        {
            "id": 54,
            "value": "5000.0000",
            "included_quantity": "60.0000",
			"quantity" : 5,
            "measure_unit_id": 6,
            "base_price_id": 18,
            "user": null,
            "recharge_value": 5500.0
        },
        {
            "id": 72,
            "value": "9000.0000",
            "included_quantity": "0.0000",
			"quantity" : 5,
            "measure_unit_id": 7,
            "base_price_id": 18,
            "user": null,
            "recharge_value": 5500.0
        }
    ],
    "services": {
        "total_price": 6500,
        "dates": [
            {
                "date_time": "2020/05/07 23:59",
                "discount_id": null,
				"discount_value": 0,
                "coupon_id": null,
                "code": null,
                "percentage": null,
                "coupon_value": null,
                "total": 6500
            }
        ]
    }
}

```

## Lista Estados de servicio

| Estado                | Id  |
| --------------------- | --- |
|En espera              |  1  |
|Asignado               |  2  |
|En transito            |  3  |
|Finalizado             |  4  |
|Cancelado              |  5  |

### Endpoint consulta tipos estado de servicio
Response:
```json
[
  {"service_state_id":1,"service_state_name":"En Espera","description":"En Espera"},
  {"service_state_id":2,"service_state_name":"Asignado","description":"Asignado"},      
  {"service_state_id":3,"service_state_name":"En Transito","description":"En Transito"},
  {"service_state_id":4,"service_state_name":"Finalizado","description":"Finalizado"}, 
  {"service_state_id":5,"service_state_name":"Cancelado","description":"Cancelado"}
]
```

## Crear Estado de servicio
Request:
```json
{
    "state": "1",
    "worker" : 88, 
    "mishap_type": 10,
    "description": ""
}
```


## Rutas de endpoints

Todas las rutas deben cumplir con los siguientes parámetros:

1.- Usar sustantivos en vez de verbos y utilizar en el mismo las acciones provistas por los métodos:

Correcto:
```
    POST /services/calculate
    GET /services/{id}
    PATCH /services/{id}
    DELETE services/{id}
 ```
Incorrecto:
 ```
    POST /services/delete/{id}
    GET /addservices
 ```
    
2.- Los nombres de las collecciones siempre deben ir en plural:
Correcto:
 ```
    POST /services/calculate
    GET /services/{id}
    PATCH /services/{id}
    DELETE services/{id}
 ```
Incorrecto:
 ```
    POST /service
    GET /service
 ```

3.- Usar anidación de forma jerarquica:
Ejemplo:
 ```
    GET /services/ <- Recupera servicios
    GET /services/{idService} <- Recupera un servicio específico
    GET /services/{idService}/stops <- Recupera las paradas de un servicio específico
    GET /services/{idService}/stops/{idStop} <- Recupera una parada de un servicio específico
    GET /services/{idService}/stops/{idStop}/evidences <- Recupera las evidencias de una parada especifica en un servicio específico
 ```

4.- Definir rutas a partir de controladores usados:
Ejemplo:

    Incorrecto:
    Controlador ReportController
```
    GET /services/reports/express
```

    Correcto:
    Controlador ReportController
 ```
    GET /reports/services/express
    GET /reports/services/runer
 ```

## Crear Estado de Parada de Servicio
Request:
```json
 {
    "stop_state_type_id":3,
    "description": null
}
```