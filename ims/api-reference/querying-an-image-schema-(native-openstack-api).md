# Querying an Image Schema \(Native OpenStack API\)<a name="EN-US_TOPIC_0020091555"></a>

## Function<a name="section10309404"></a>

This API is used to query the image schema, which allows you to view image attributes and their data types.

## URI<a name="section25675773"></a>

GET /v2/schemas/image

## Request<a name="section29755367"></a>

-   Request parameters

    None

-   Example request

    ```
    GET https://{Endpoint}/v2/schemas/image
    ```


## Response<a name="section66471715"></a>

-   Response parameters

    <a name="table1672858311351"></a>
    <table><thead align="left"><tr id="row3075245411351"><th class="cellrowborder" valign="top" width="30.646935306469352%" id="mcps1.1.4.1.1"><p id="p792088511351"><a name="p792088511351"></a><a name="p792088511351"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="17.18828117188281%" id="mcps1.1.4.1.2"><p id="p5897662019837"><a name="p5897662019837"></a><a name="p5897662019837"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="52.16478352164784%" id="mcps1.1.4.1.3"><p id="p3761198111351"><a name="p3761198111351"></a><a name="p3761198111351"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row2667160511351"><td class="cellrowborder" valign="top" width="30.646935306469352%" headers="mcps1.1.4.1.1 "><p id="p1291637311351"><a name="p1291637311351"></a><a name="p1291637311351"></a>additionalProperties</p>
    </td>
    <td class="cellrowborder" valign="top" width="17.18828117188281%" headers="mcps1.1.4.1.2 "><p id="p1237692119837"><a name="p1237692119837"></a><a name="p1237692119837"></a>Object</p>
    </td>
    <td class="cellrowborder" valign="top" width="52.16478352164784%" headers="mcps1.1.4.1.3 "><p id="p3959330211351"><a name="p3959330211351"></a><a name="p3959330211351"></a>Specifies the additional attributes.</p>
    </td>
    </tr>
    <tr id="row2079540211351"><td class="cellrowborder" valign="top" width="30.646935306469352%" headers="mcps1.1.4.1.1 "><p id="p670601511351"><a name="p670601511351"></a><a name="p670601511351"></a>name</p>
    </td>
    <td class="cellrowborder" valign="top" width="17.18828117188281%" headers="mcps1.1.4.1.2 "><p id="p6300656319837"><a name="p6300656319837"></a><a name="p6300656319837"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="52.16478352164784%" headers="mcps1.1.4.1.3 "><p id="p631632811351"><a name="p631632811351"></a><a name="p631632811351"></a>Specifies the schema name.</p>
    </td>
    </tr>
    <tr id="row5684695611351"><td class="cellrowborder" valign="top" width="30.646935306469352%" headers="mcps1.1.4.1.1 "><p id="p4120070311351"><a name="p4120070311351"></a><a name="p4120070311351"></a>links</p>
    </td>
    <td class="cellrowborder" valign="top" width="17.18828117188281%" headers="mcps1.1.4.1.2 "><p id="p325796919837"><a name="p325796919837"></a><a name="p325796919837"></a>Array of objects</p>
    </td>
    <td class="cellrowborder" valign="top" width="52.16478352164784%" headers="mcps1.1.4.1.3 "><p id="p4892261811351"><a name="p4892261811351"></a><a name="p4892261811351"></a>Specifies the URL for accessing the schema.</p>
    <p id="p8416185214528"><a name="p8416185214528"></a><a name="p8416185214528"></a>For details, see <a href="#table15641103183416">Table 1</a>.</p>
    </td>
    </tr>
    <tr id="row3765038211351"><td class="cellrowborder" valign="top" width="30.646935306469352%" headers="mcps1.1.4.1.1 "><p id="p2978213811351"><a name="p2978213811351"></a><a name="p2978213811351"></a>properties</p>
    </td>
    <td class="cellrowborder" valign="top" width="17.18828117188281%" headers="mcps1.1.4.1.2 "><p id="p6256894019837"><a name="p6256894019837"></a><a name="p6256894019837"></a>Object</p>
    </td>
    <td class="cellrowborder" valign="top" width="52.16478352164784%" headers="mcps1.1.4.1.3 "><p id="p339831010531"><a name="p339831010531"></a><a name="p339831010531"></a>Describes basic image attributes, including the type and usage of each attribute.</p>
    <p id="p4120204111445"><a name="p4120204111445"></a><a name="p4120204111445"></a>For details about the parameters, see <a href="image-attributes.md">Image Attributes</a>.</p>
    </td>
    </tr>
    </tbody>
    </table>

    **Table  1**  LinkInfo parameter description

    <a name="table15641103183416"></a>
    <table><thead align="left"><tr id="row136411132345"><th class="cellrowborder" valign="top" width="30.646935306469352%" id="mcps1.2.4.1.1"><p id="p136411433347"><a name="p136411433347"></a><a name="p136411433347"></a>Parameter</p>
    </th>
    <th class="cellrowborder" valign="top" width="17.18828117188281%" id="mcps1.2.4.1.2"><p id="p12641193183412"><a name="p12641193183412"></a><a name="p12641193183412"></a>Type</p>
    </th>
    <th class="cellrowborder" valign="top" width="52.16478352164784%" id="mcps1.2.4.1.3"><p id="p164120311348"><a name="p164120311348"></a><a name="p164120311348"></a>Description</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row4641634345"><td class="cellrowborder" valign="top" width="30.646935306469352%" headers="mcps1.2.4.1.1 "><p id="p126411432347"><a name="p126411432347"></a><a name="p126411432347"></a>href</p>
    </td>
    <td class="cellrowborder" valign="top" width="17.18828117188281%" headers="mcps1.2.4.1.2 "><p id="p1864133173419"><a name="p1864133173419"></a><a name="p1864133173419"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="52.16478352164784%" headers="mcps1.2.4.1.3 "><p id="p16411373420"><a name="p16411373420"></a><a name="p16411373420"></a>Specifies the domain name.</p>
    </td>
    </tr>
    <tr id="row146411238348"><td class="cellrowborder" valign="top" width="30.646935306469352%" headers="mcps1.2.4.1.1 "><p id="p156421039346"><a name="p156421039346"></a><a name="p156421039346"></a>rel</p>
    </td>
    <td class="cellrowborder" valign="top" width="17.18828117188281%" headers="mcps1.2.4.1.2 "><p id="p196421736343"><a name="p196421736343"></a><a name="p196421736343"></a>String</p>
    </td>
    <td class="cellrowborder" valign="top" width="52.16478352164784%" headers="mcps1.2.4.1.3 "><p id="p1164263163416"><a name="p1164263163416"></a><a name="p1164263163416"></a>Specifies the domain name description.</p>
    </td>
    </tr>
    </tbody>
    </table>

-   Example response

    ```
    STATUS CODE 200
    ```

    ```
    {
        "additionalProperties": {
            "type": "string"
        },
        "name": "image",
        "links": [
            {
                "href": "{self}",
                "rel": "self"
            },
            {
                "href": "{file}",
                "rel": "enclosure"
            },
            {
                "href": "{schema}",
                "rel": "describedby"
            }
        ],
        "properties": {
            "status": {
                "enum": [
                    "queued",
                    "saving",
                    "active",
                    "killed",
                    "deleted",
                    "pending_delete"
                ],
                "type": "string",
                "description": "Status of the image (READ-ONLY)"
            },
            "tags": {
                "items": {
                    "type": "string",
                    "maxLength": 255
                },
                "type": "array",
                "description": "List of strings related to the image"
            },
            "kernel_id": {
                "pattern": "^([0-9a-fA-F]){8}-([0-9a-fA-F]){4}-([0-9a-fA-F]){4}-([0-9a-fA-F]){4}-([0-9a-fA-F]){12}$",
                "type": "string",
                "description": "ID of image stored in Glance that should be used as the kernel when booting an AMI-style image.",
                "is_base": false
            },
            "container_format": {
                "enum": [
                    "ami",
                    "ari",
                    "aki",
                    "bare",
                    "ovf",
                    "ova"
                ],
                "type": "string",
                "description": "Format of the container"
            },
            "min_ram": {
                "type": "integer",
                "description": "Amount of ram (in MB) required to boot image."
            },
            "ramdisk_id": {
                "pattern": "^([0-9a-fA-F]){8}-([0-9a-fA-F]){4}-([0-9a-fA-F]){4}-([0-9a-fA-F]){4}-([0-9a-fA-F]){12}$",
                "type": "string",
                "description": "ID of image stored in Glance that should be used as the ramdisk when booting an AMI-style image.",
                "is_base": false
            },
            "locations": {
                "items": {
                    "required": [
                        "url",
                        "metadata"
                    ],
                    "type": "object",
                    "properties": {
                        "url": {
                            "type": "string",
                            "maxLength": 255
                        },
                        "metadata": {
                            "type": "object"
                        }
                    }
                },
                "type": "array",
                "description": "A set of URLs to access the image file kept in external store"
            },
            "visibility": {
                "enum": [
                    "public",
                    "private"
                ],
                "type": "string",
                "description": "Scope of image accessibility"
            },
            "updated_at": {
                "type": "string",
                "description": "Date and time of the last image modification (READ-ONLY)"
            },
            "owner": {
                "type": "string",
                "description": "Owner of the image",
                "maxLength": 255
            },
            "file": {
                "type": "string",
                "description": "(READ-ONLY)"
            },
            "min_disk": {
                "type": "integer",
                "description": "Amount of disk space (in GB) required to boot image."
            },
            "virtual_size": {
                "type": "integer",
                "description": "Virtual size of image in bytes (READ-ONLY)"
            },
            "id": {
                "pattern": "^([0-9a-fA-F]){8}-([0-9a-fA-F]){4}-([0-9a-fA-F]){4}-([0-9a-fA-F]){4}-([0-9a-fA-F]){12}$",
                "type": "string",
                "description": "An identifier for the image"
            },
            "size": {
                "type": "integer",
                "description": "Size of image file in bytes (READ-ONLY)"
            },
            "instance_uuid": {
                "type": "string",
                "description": "ID of instance used to create this image.",
                "is_base": false
            },
            "os_distro": {
                "type": "string",
                "description": "Common name of operating system distribution as specified in http://docs.openstack.org/trunk/openstack-compute/admin/content/adding-images.html",
                "is_base": false
            },
            "name": {
                "type": "string",
                "description": "Descriptive name for the image",
                "maxLength": 255
            },
            "checksum": {
                "type": "string",
                "description": "md5 hash of image contents. (READ-ONLY)",
                "maxLength": 32
            },
            "created_at": {
                "type": "string",
                "description": "Date and time of image registration (READ-ONLY)"
            },
            "disk_format": {
                "enum": [
                    "ami",
                    "ari",
                    "aki",
                    "vhd",
                    "vmdk",
                    "raw",
                    "qcow2",
                    "vdi",
                    "iso"
                ],
                "type": "string",
                "description": "Format of the disk"
            },
            "os_version": {
                "type": "string",
                "description": "Operating system version as specified by the distributor",
                "is_base": false
            },
            "protected": {
                "type": "boolean",
                "description": "If true, image will not be deletable."
            },
            "architecture": {
                "type": "string",
                "description": "Operating system architecture as specified in http://docs.openstack.org/trunk/openstack-compute/admin/content/adding-images.html",
                "is_base": false
            },
            "direct_url": {
                "type": "string",
                "description": "URL to access the image file kept in external store (READ-ONLY)"
            },
            "self": {
                "type": "string",
                "description": "(READ-ONLY)"
            },
            "schema": {
                "type": "string",
                "description": "(READ-ONLY)"
            }
        }
    }
    ```


## Returned Values<a name="section61374531"></a>

-   Normal

    200

-   Abnormal

    <a name="table271454817439"></a>
    <table><thead align="left"><tr id="row3541095017439"><th class="cellrowborder" valign="top" width="46.54%" id="mcps1.1.3.1.1"><p id="p4971469317439"><a name="p4971469317439"></a><a name="p4971469317439"></a><strong id="b27937296162044"><a name="b27937296162044"></a><a name="b27937296162044"></a>Returned Value</strong></p>
    </th>
    <th class="cellrowborder" valign="top" width="53.459999999999994%" id="mcps1.1.3.1.2"><p id="p35835717439"><a name="p35835717439"></a><a name="p35835717439"></a><strong id="b2568302162048"><a name="b2568302162048"></a><a name="b2568302162048"></a>Description</strong></p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row2902697417439"><td class="cellrowborder" valign="top" width="46.54%" headers="mcps1.1.3.1.1 "><p id="p237466317439"><a name="p237466317439"></a><a name="p237466317439"></a>400 Bad Request</p>
    </td>
    <td class="cellrowborder" valign="top" width="53.459999999999994%" headers="mcps1.1.3.1.2 "><p id="p5812997617439"><a name="p5812997617439"></a><a name="p5812997617439"></a>Request error.</p>
    </td>
    </tr>
    <tr id="row5340773917439"><td class="cellrowborder" valign="top" width="46.54%" headers="mcps1.1.3.1.1 "><p id="p3105962817439"><a name="p3105962817439"></a><a name="p3105962817439"></a>401 Unauthorized</p>
    </td>
    <td class="cellrowborder" valign="top" width="53.459999999999994%" headers="mcps1.1.3.1.2 "><p id="p3280197817439"><a name="p3280197817439"></a><a name="p3280197817439"></a>Authentication failed.</p>
    </td>
    </tr>
    <tr id="row2678235117439"><td class="cellrowborder" valign="top" width="46.54%" headers="mcps1.1.3.1.1 "><p id="p2188683517439"><a name="p2188683517439"></a><a name="p2188683517439"></a>403 Forbidden</p>
    </td>
    <td class="cellrowborder" valign="top" width="53.459999999999994%" headers="mcps1.1.3.1.2 "><p id="p2800317417439"><a name="p2800317417439"></a><a name="p2800317417439"></a>You do not have the rights to perform the operation.</p>
    </td>
    </tr>
    <tr id="row16775501191954"><td class="cellrowborder" valign="top" width="46.54%" headers="mcps1.1.3.1.1 "><p id="p19013873191957"><a name="p19013873191957"></a><a name="p19013873191957"></a>404 Not Found</p>
    </td>
    <td class="cellrowborder" valign="top" width="53.459999999999994%" headers="mcps1.1.3.1.2 "><p id="p63728762191957"><a name="p63728762191957"></a><a name="p63728762191957"></a>The requested resource was not found.</p>
    </td>
    </tr>
    <tr id="row5070198217439"><td class="cellrowborder" valign="top" width="46.54%" headers="mcps1.1.3.1.1 "><p id="p1321988617439"><a name="p1321988617439"></a><a name="p1321988617439"></a>500 Internal Server Error</p>
    </td>
    <td class="cellrowborder" valign="top" width="53.459999999999994%" headers="mcps1.1.3.1.2 "><p id="p6417782617439"><a name="p6417782617439"></a><a name="p6417782617439"></a>Internal service error.</p>
    </td>
    </tr>
    <tr id="row4072952517439"><td class="cellrowborder" valign="top" width="46.54%" headers="mcps1.1.3.1.1 "><p id="p1075724317439"><a name="p1075724317439"></a><a name="p1075724317439"></a>503 Service Unavailable</p>
    </td>
    <td class="cellrowborder" valign="top" width="53.459999999999994%" headers="mcps1.1.3.1.2 "><p id="p6603036117439"><a name="p6603036117439"></a><a name="p6603036117439"></a>The service is unavailable.</p>
    </td>
    </tr>
    </tbody>
    </table>


