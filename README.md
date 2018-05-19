Dockerfile for the Zelda: A Link to the Past randomizer

https://github.com/sporchia/alttp_vt_randomizer

Usage:
Copy the proper ROM file to a local directory, and swap out the directory for "alttp_dir" below.

    docker run -v /home/$USER/alttp_dir/rom:/rom tomfaulkner80/alttp_sm_combo_randomizer /rom/alttp.sfc /rom
