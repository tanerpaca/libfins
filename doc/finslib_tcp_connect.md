# Libfins API Reference

### `finslib_tcp_connect( sys, address, port, local_net, local_node, local_unit, remote_net, remote_node, remote_unit, error_val, error_max );`

### Parameters

| Parameter | Type | Description |
| :--- | :--- | :--- |
|**`sys`**|`struct fins_sys_tp *`|A pointer to a structure with the FINS context|
|**`address`**|`const char *`|The IP address of the remote node|
|**`port`**|`uint16_t`|The TCP port to communicate on|
|**`local_net`**|`uint8_t`|The local network number|
|**`local_node`**|`uint8_t`|The local node number|
|**`local_unit`**|`uint8_t`|The local unit number|
|**`remote_net`**|`uint8_t`|The remote network number|
|**`remote_node`**|`uint8_t`|The remote node number|
|**`remote_unit`**|`uint8_t`|The remote unit number|
|**`error_val`**|`int *`|The error code if an error occured|
|**`error_max`**|`int`|The maximum error code|

### Returns

| Type | Description |
| :--- | :--- |
|`int`|A return value from the list [`FINS_RETVAL_...`](FINS_RETVAL.md) indicating the result of the query|

### Description

### See Also

* [`FINS_RETVAL...`](FINS_RETVAL.md) &ndash; Libfins function return code list
* [`finslib_disconnect();`](finslib_disconnect.md)