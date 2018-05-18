---
Description: 'The photo metadata policy for the System.GPS.AltitudeRef property.'
ms.assetid: 'abbb2441-25ca-484b-a744-620ff2794221'
title: 'System.GPS.AltitudeRef Photo Metadata Policy'
---

# System.GPS.AltitudeRef Photo Metadata Policy

The photo metadata policy for the [System.GPS.AltitudeRef](http://msdn.microsoft.com/en-us/library/bb787478(VS.85).aspx) property.

### PKEY

PKEY\_GPS\_AltitudeRef

### Description

Indicates the altitude used as the reference altitude. A value of 0 indicates the altitude is above sea level. A value of 1 indicates an altitude below sea level.

### Containers

JPEG, TIFF

### Read-Only

No

### Output PROPVARIANT Type

VT\_UI1

### Input Type

Byte.

### Conflict Resolution Policy

Values from different schemas are reconciled.

### JPEG Policies

### Read Paths



| Order | Path                     | Disk Format |
|-------|--------------------------|-------------|
| 1     | /app1/ifd/gps/{ushort=5} | byte        |
| 2     | /xmp/exif:GPSAltitudeRef | unicode     |



 

### Write Paths



| Order | Path                     | Disk Format |
|-------|--------------------------|-------------|
| 1     | /app1/ifd/gps/{ushort=5} | byte        |
| 2     | /xmp/exif:GPSAltitudeRef | unicode     |



 

### Remove Paths



| Order | Path                     |
|-------|--------------------------|
| 1     | /app1/ifd/gps/{ushort=5} |
| 2     | /xmp/exif:gpsaltituderef |



 

### TIFF Policies

### Read Paths



| Order | Path                         | Disk Format |
|-------|------------------------------|-------------|
| 1     | /ifd/gps/{ushort=5}          | byte        |
| 2     | /ifd/xmp/exif:GPSAltitudeRef | unicode     |



 

### Write Paths



| Order | Path                         | Disk Format |
|-------|------------------------------|-------------|
| 1     | /ifd/gps/{ushort=5}          | byte        |
| 2     | /ifd/xmp/exif:GPSAltitudeRef | unicode     |



 

### Remove Paths



| Order | Path                         |
|-------|------------------------------|
| 1     | /ifd/gps/{ushort=5}          |
| 2     | /ifd/xmp/exif:gpsaltituderef |



 

## Remarks

## Related topics

<dl> <dt>

[System.GPS.AltitudeRef](http://msdn.microsoft.com/en-us/library/bb787478(VS.85).aspx)
</dt> </dl>

 

 


