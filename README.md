# potential_methods_processing

Some useful processes implementations to apply on 2D magnetic and gravimetric data:


## Reduction to the pole (rtp);

  ![](rtp_md0_mi45.png)

  Changes geology magnetization and ambient field direction to vertical (up).


## Reduction to the equator (rte); and

  ![](rte_md0_mi45.png)

  Changes geology magnetization to upward and ambient field direction to north.


## Analytic signal aplitude (asa).

  ![](asa45.png)

  Is the envelope of the the complex signal (via Hilbert transform). It is useful when Hilbert transform is performed on the magnetization direction axis. In this case, the anomalies fall to the magnetic source position. Bellow image (from Wikipedia) helps understanding the concept of envelope (in red).

  ![](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d7/Analytic.svg/1024px-Analytic.svg.png)



## Upward continuation (uc);

  ![](uc_dz03.png)

  Sees the data as if it was measured from a higher quota plan (it means moving away from the sources);


## Downward continuation (dc);

  ![](dc_dz0.1.png)

  Sees the data as if it was measured from a lower quota plan (it means moving near the sources).


# Example data used

The magnetic data used as example were modeled with the routines present in Richard j. Blakely's "Potential Theory in Gravity and Magnetic Applications"'s Apendix B.
