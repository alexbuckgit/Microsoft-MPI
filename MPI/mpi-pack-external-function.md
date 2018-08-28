﻿---
title: MPI_Pack_external function
TOCTitle: MPI_Pack_external function
ms:assetid: c2051da8-9986-49f7-b19b-feb1d45d9a56
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Dn473441(v=VS.85)
ms:contentKeyID: 59360977
ms.date: 03/28/2018
mtps_version: v=VS.85
f1_keywords:
- MPI_PACK_EXTERNAL
- mpif/MPI_Pack_external
- mpi/MPI_PACK_EXTERNAL
dev_langs:
- C++
- C
---

# MPI\_Pack\_external function

TBD

## Syntax

``` c++
int MPIAPI MPI_Pack_external(
       _In_z_ char                 *datarep,
  _In_ void                        *inbuf,
       int                         incount,
       MPI_Datatype                datatype,
       _Out_bytecap_(outsize) void *outbuf,
       MPI_Aint                    outsize,
       _Inout_ MPI_Aint            *position
);
```

## Parameters

  - *datarep*  
    TBD

  - *inbuf* \[in\]  
    TBD

  - *incount*  
    TBD

  - *datatype*  
    TBD

  - *outbuf*  
    TBD

  - *outsize*  
    TBD

  - *position*  
    TBD

## Return value

TBD

## Fortran

    MPI_PACK_EXTERNAL(DATAREP, INBUF, INCOUNT, DATATYPE, OUTBUF, OUTSIZE,
                POSITION, IERROR)
        INTEGER INCOUNT, DATATYPE, IERROR
        INTEGER(KIND=MPI_ADDRESS_KIND) OUTSIZE, POSITION
        CHARACTER*(*) DATAREP
        <type> INBUF(*), OUTBUF(*)

## Requirements

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Product</p></td>
<td><p>HPC Pack 2012 MS-MPI Redistributable Package, HPC Pack 2008 R2 MS-MPI Redistributable Package, HPC Pack 2008 MS-MPI Redistributable Package or HPC Pack 2008 Client Utilities</p></td>
</tr>
<tr class="even">
<td><p>Header</p></td>
<td>Mpi.h;
Mpif.h</td>
</tr>
<tr class="odd">
<td><p>Library</p></td>
<td>Msmpi.lib</td>
</tr>
<tr class="even">
<td><p>DLL</p></td>
<td>Msmpi.dll</td>
</tr>
</tbody>
</table>


## See also

[MPI Datatype Functions](mpi-datatype-functions.md)
