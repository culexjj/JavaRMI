# JavaRMI
Practica UNED Sistemas Distribuidos 2017-2018

El propósito de la práctica es el desarrollo de un software que gestione un proceso de comercio electrónico mediante Java RMI.
En este sistema actuaran tres tipos de actores cuyas funciones se listan a continuación:
1.- Regulador: La entidad Regulador se encarga de regular el proceso de compra por red para ello activa dos servicios:
 Servicio Autenticación: Las entidades clientes y las entidades distribuidores se tienen que dar de alta en el sistema para poder operar y realizar operaciones de compra/venta. La autenticación se lleva a cabo cuando el servicio devuelve a la entidad demandante (cliente o distribuidor) un identificador único con el que registrar cualquier operación en el sistema.
 Servicio Mercancías: Este servicio se encarga de registrar las mercancías demandadas por los clientes y las ofertas que hacen los distribuidores. La finalidad del mismo es enviar las ofertas de mercancías de los distribuidores a los clientes que soliciten una o unas determinadas mercancías.
2.- Distribuidores: Estas entidades son las encargadas de ofertar sus mercancías con la intención que lleguen a los clientes que las solicitan. Cuando un Cliente está interesado en una determinada oferta de un Distribuidor, éste completa la venta mediante su servicio de venta.
3.- Clientes: Son los compradores. Se registran en el sistema a través del Regulador y esperan a que les lleguen las ofertas de mercancías. Cuando le llega una que le interesa accede al servicio de venta del Distribuidor y completan la operación.
