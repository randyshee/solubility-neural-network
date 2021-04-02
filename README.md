# solubility-neural-network

This is a project that predicts solubilities of molecules from their fingerprints using a neural network. The fingerprints of molecules were extracted from the SMILES form of the molecules using the `AllChem.GetMorganFingerprintAsBitVect` method from the RDKit. And this fingerprint data were then converted into numpy arrays using the `DataStructs.ConvertToNumpyArray` method so that they would become arrays with elements being 0 or 1 that could then be passed into the neural network.
