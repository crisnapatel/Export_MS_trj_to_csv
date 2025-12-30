# Export_MS_trj_to_csv
A perl script that reads Materials Studio (2020.1v) forcite trajectory file and write a txt file (in lammps dump format) that can be read by ovito.
`export_trajectory_chunked.pl`: writes lammps format dump file of all atoms. Read the perl script for more.
`export_sets_trajectory.pl`: writes lammps format dump file of only the `Sets` defined in the perl script. Read more about `Sets` in MS doc.
