## Listado de Servicios o 1 servicio

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

```json
//EXPRESS
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

### Endpoint consulta
```json
[
  {"id":1,"name":"En Espera","description":"En Espera"},
  {"id":2,"name":"Asignado","description":"Asignado"},      
  {"id":3,"name":"En Transito","description":"En Transito"},
  {"id":4,"name":"Finalizado","description":"Finalizado"}, 
  {"id":5,"name":"Cancelado","description":"Cancelado"}
]
```

## Rutas de endpoints


  

    //>service types
    $router->get('/servicetypes', 'Express\ServiceTypeController@show');
    $router->post('/servicetypes', 'Express\ServiceTypeController@create');
    $router->put('/servicetypes/{id}', 'Express\ServiceTypeController@update');
    $router->patch('/servicetypes/{id}', 'Express\ServiceTypeController@edit');
    $router->delete('/servicetypes/{id}', 'Express\ServiceTypeController@delete');

    //>payment types
    $router->get('/paymenttypes', 'Express\PaymentTypeController@show');
    $router->post('/paymenttypes', 'Express\PaymentTypeController@create');
    $router->put('/paymenttypes/{id}', 'Express\PaymentTypeController@update');
    $router->patch('/paymenttypes/{id}', 'Express\PaymentTypeController@edit');
    $router->delete('/paymenttypes/{id}', 'Express\PaymentTypeController@delete');

    //>service modalities
    $router->get('/servicemodalities', 'Express\ServiceModalityController@show');
    $router->post('/servicemodalities', 'Express\ServiceModalityController@create');
    $router->put('/servicemodalities/{id}', 'Express\ServiceModalityController@update');
    $router->patch('/servicemodalities/{id}', 'Express\ServiceModalityController@edit');
    $router->delete('/servicemodalities/{id}', 'Express\ServiceModalityController@delete');

    //Services
    $router->get('/services/{id}/details', 'Express\ServiceController@details');
    $router->post('/services', 'Express\ServiceController@create');
    $router->post('/services/calculate', 'Express\ServiceController@calculate');
    $router->get('/services/{id}', 'Express\ServiceController@showOne');
    $router->get('/services', 'Express\ServiceController@show');
    // $router->put('/services/{id}', 'Express\ServiceController@update');
    $router->patch('/services/{id}', 'Express\ServiceController@edit');
    $router->delete('/services/{id}', 'Express\ServiceController@delete');
    $router->get('/services/{id}/stops', 'Express\ServiceController@serviceStop');
    $router->get('/services/{id}/dates', 'Express\ServiceController@serviceDate');

    // $router->post('/services/{id}/invoice', 'Express\ServiceController@invoice');

    $router->patch('/services/{id}/stops', 'Express\ServiceController@serviceOrderStopUpdate');
    $router->put('/services/{id}/stops', 'Express\ServiceController@serviceStopUpdate');
    $router->delete('/services/{id}/stops', 'Express\ServiceController@serviceStopDelete');


    $router->patch('/services/{id}/dates/{idDate}', 'Express\ServiceController@serviceDateEdit');
    $router->put('/services/{id}/dates', 'Express\ServiceController@datesUpdate');
    //$router->delete('/services/{id}/dates', 'Express\ServiceController@datesDelete');
    $router->post('/services/{id}/stops/{idStop}/states', 'Express\ServiceController@stopStateCreate');
    $router->get('/services/{id}/stops/{idStop}/states', 'Express\ServiceController@stopStateShow');

    $router->post('/services/{id}/stops/{idStop}/evidences', 'Express\ServiceController@stopEvidenceCreate');

    $router->get('/services/{idService}/stops/{idStop}/evidence', 'Express\StopEvidenceController@show');
    $router->get('/services/{id}/stops/{idStop}/evidences', 'Express\ServiceController@stopEvidence');

    $router->get('/services/{id}/states', 'Express\ServiceController@states');
    $router->post('/services/{id}/states', 'Express\ServiceController@statesCreate');

    //>Gains
    $router->get('/services/{id}/workers/{idWorker}/calculategains', 'Express\ServiceController@getGains');
    //> Relaunch Service
    $router->post('/services/relaunch/{id}', 'Express\ServiceController@relaunchService');


    $router->get('/transactions', 'Express\TransactionController@show');
    $router->post('/transactions', 'Express\TransactionController@create');

    $router->post('/services/{id}/relaunch', 'Express\ServiceController@relaunchService');

    //>Workers
    $router->get('/workers', 'Express\WorkerController@show');
    $router->get('/workers/{id}', 'Express\WorkerController@showOne');
    $router->patch('/workers/{id}', 'Express\WorkerController@edit');
    $router->delete('/workers/{id}', 'Express\WorkerController@delete');
    $router->post('/workers', 'Express\WorkerController@create');
    $router->post('/workers/register', 'Express\WorkerController@register');
    $router->post('/workers/{id}/vehicles', 'Express\WorkerController@vehicleCreate');
    $router->patch('/workers/{id}/vehicles/{vehicle}', 'Express\WorkerController@vehicleEdit');
    $router->get('/workers/{id}/vehicles', 'Express\WorkerController@vehicleShow');
    $router->post('/workers/vehicles/{id}/file', 'Express\WorkerController@uploadDocument');
    $router->get('/workers/app/{id}/version/{version}', 'Express\WorkerController@app');
    $router->post('/workers/app/{id}/fraud', 'Express\WorkerController@fraud');
    $router->get('/workers/status/{id}', 'Express\WorkerController@status');

    //>Rankings
    $router->get('/rankings', 'Express\RankingController@show');
    $router->get('/rankings/{id}', 'Express\RankingController@showOne');
    $router->patch('/rankings/{id}', 'Express\RankingController@edit');
    $router->delete('/rankings/{id}', 'Express\RankingController@delete');
    $router->post('/rankings', 'Express\RankingController@create');
    $router->post('/rankings/{id}/vehicles', 'Express\RankingController@vehicleCreate');
    $router->get('/rankings/{id}/vehicles', 'Express\RankingController@vehicleShow');

    //>Type States Service
    $router->get('/servicestatetypes', 'Express\ServiceStateTypeController@show');

    //>Type States Stop Service
    $router->get('/servicestopstatetypes', 'Express\StopStateTypeController@show');

    //reports
    $router->post('/services/reports', 'ReportController@showServicesExpress');
    $router->post('/workers/reports', 'ReportController@showWorkersExpress');
    $router->post('/reports/vehicles', 'ReportController@showVehiclesExpress');

    $router->post('/reports/user', 'ReportController@showUsers');
    $router->post('/reports/companies', 'ReportController@showUsersInCompanies');

    //Recharges
    $router->get('/services/{id}/recharges', 'Express\RechargeController@show');
    $router->post('/services/{id}/recharges', 'Express\RechargeController@create');

    //Petitions
    $router->get('/petitions', 'Express\PetitionController@show');
    $router->get('/petitions/{id}', 'Express\PetitionController@showOne');
    $router->post('/petitions', 'Express\PetitionController@create');
    $router->post('/petitions/{id}', 'Express\PetitionController@edit');
    $router->delete('/petitions/{id}', 'Express\PetitionController@delete');
    $router->post('petitions/{id}/documents', 'Express\PetitionController@editDocument');
    $router->post('/documents', 'Express\PetitionController@editDocumentWorker');




