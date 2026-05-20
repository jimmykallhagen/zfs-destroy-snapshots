# Lists all ZFS datasets that have snapshots so you can choose to bulk delete all of them for that specific dataset

```Fish
  ╔═══════════════════════════════════════════════════════════╗
  ║     Nordix: ZFS Snapshot Destroyer - Interactive Mode     ║
  ╚═══════════════════════════════════════════════════════════╝


============================================
  Datasets with Snapshots
============================================

  [ 1]  nordix                                   (2 snapshots)
  [ 2]  nordix/home                              (3 snapshots)
  [ 3]  nordix/home/cache                        (3 snapshots)
  [ 4]  nordix/home/config                       (3 snapshots)
  [ 5]  nordix/home/documents                    (3 snapshots)
  [ 6]  nordix/home/downloads                    (3 snapshots)
  [ 7]  nordix/home/games                        (3 snapshots)
  [ 8]  nordix/home/local                        (3 snapshots)
  [ 9]  nordix/home/local/lutris                 (3 snapshots)
  [10]  nordix/home/local/steam                  (3 snapshots)
  [11]  nordix/home/local/steam/game             (2 snapshots)
  [12]  nordix/home/local/steam/proton           (3 snapshots)
  [13]  nordix/home/local/steam/shadercache      (3 snapshots)
  [14]  nordix/home/music                        (3 snapshots)
  [15]  nordix/home/pictures                     (3 snapshots)
  [16]  nordix/home/videos                       (3 snapshots)
  [17]  nordix/home/wine-prefix                  (3 snapshots)
  [18]  nordix/library                           (2 snapshots)
  [19]  nordix/opt                               (2 snapshots)
  [20]  nordix/ROOT                              (2 snapshots)
  [21]  nordix/ROOT/default                      (4 snapshots)
  [22]  nordix/ROOT/frozen                       (2 snapshots)
  [23]  nordix/tmp                               (2 snapshots)
  [24]  nordix/varcache                          (3 snapshots)
  [25]  nordix/varlib                            (3 snapshots)
  [26]  nordix/varlib/b72861760213a7856cc154642b6140cc8278bfea9e0d41bba71f8e5d0aeb3c34 (1 snapshots)
  [27]  nordix/varlog                            (2 snapshots)
  [28]  nordix/vartmp                            (3 snapshots)
  [29]  nordix/vm                                (2 snapshots)
  [30]  tank/data-flytt                          (1 snapshots)
  [31]  tank/media                               (1 snapshots)

--------------------------------------------
  [q]   Quit
--------------------------------------------

Enter selection number (or 'q' to quit):
```

```Fish
Enter selection number (or 'q' to quit): 1

╔════════════════════════════════════════════════════════════════╗
║                        ⚠️  WARNING ⚠️                            ║
╠════════════════════════════════════════════════════════════════╝
║ You are about to destroy ALL snapshots for:
║
║  Dataset: nordix
║
║  Number of snapshots to be destroyed: 2
║
║
║                THIS ACTION CANNOT BE UNDONE!
╚═════════════════════════════════════════════════════════════════

Is this the dataset you want to delete all snapshots from?
Type 'yes' to confirm, or anything else to cancel:
```
```Fish

Destroying snapshots for: nordix
--------------------------------------------
  Destroying: nordix@Base
    ✓ Success
  Destroying: nordix@base2
    ✓ Success

Done! All snapshots for nordix have been processed.

Press Enter to continue...
```
