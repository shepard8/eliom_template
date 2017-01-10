# eliom_template

You can clone this repository to get a ready-to-use OASIS environment with an Ocsigen/Eliom application (with JavaScript enabled).

To test if everything is going well:

    oasis setup
    ocaml setup.ml -configure
    ocaml setup.ml -build
    ocsigenserver -c run.conf -v
    
Current version of Eliom supported: 6.1.
    
This template is based on an idea from @TobiasBora. Thanks to him!
