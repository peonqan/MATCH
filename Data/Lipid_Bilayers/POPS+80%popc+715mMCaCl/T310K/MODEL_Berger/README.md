#Data from https://doi.org/10.5281/zenodo.887399
wget https://zenodo.org/record/887400/files/traj.xtc
wget https://zenodo.org/record/887400/files/topol.tpr
mv traj.xtc trajectory.xtc
cp ~/NMRlipids/MATCH/MAPPING/mappingPOPSberger.txt ./mappingFILEpops.txt
cp ~/NMRlipids/MATCH/scratch/report/gro_OP.awk ./
cp ../../../../../MAPPING/mappingPOPCberger.txt ./mappingFILEpopc.txt
wget https://zenodo.org/record/887400/files/conf.gro
wget https://zenodo.org/record/887400/files/ions_scaled_miriam.itp
wget https://zenodo.org/record/887400/files/ions_scaled_miriam_ffgmx.itp
wget https://zenodo.org/record/887400/files/ions_scaled_miriam_ffgmxnb.itp
wget https://zenodo.org/record/887400/files/ions_scaled_miriam_lipid.itp
wget https://zenodo.org/record/887400/files/popc.itp
wget https://zenodo.org/record/887400/files/topol.top
