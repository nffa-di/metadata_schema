parser.py: the NOMAD Yambo parser in https://github.com/Jajar26/nomad-parser-plugins-simulation/blob/extend-yambo/src/nomad_simulation_parsers/parsers/yambo/parser.py, where we (E. Molteni, H. Belgroun) are implementing (work in progress) the parsing of Yambo optical spectra: see in particular: the function get_spectra and the "spectra files" part;
our Pull Request: https://github.com/FAIRmat-NFDI/nomad-parser-plugins-simulation/pull/158


Our corresponding contribution to the legacy NOMAD Yambo parser plugin electronic-parsers: 
parser: https://github.com/Jajar26/electronic-parsers/blob/develop/electronicparsers/yambo/parser.py: see in particular lines 735-771;
metainfo: https://github.com/Jajar26/electronic-parsers/blob/develop/electronicparsers/yambo/metainfo/yambo.py: see in particular the x_yambo_sp_type quantity; 
Pull Request: https://github.com/nomad-coe/electronic-parsers/pull/292;
Issue about the need of adding  'Polarizability' and 'Dielectric function' to the method_name list in datamodel/results.py
