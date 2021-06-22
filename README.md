# miscellaneous-grouping
using System;
using System.Collections.Generic;
using System.IO;

namespace cern2
{
    class Program
    {
     

        static readonly string textFile = @"C:\Users\user\Desktop\text.txt";

        static void Main(string[] args)
        {

            List<string> DStarToD0Pi = new List<string>();
            List<string> DsToTauNeutrinoToMuMuMuNeutrino = new List<string>();
            List<string> EEG = new List<string>();
            List<string> ExtendedWeakIsospinModel = new List<string>();
            List<string> GluGluSpin0ToGG = new List<string>();
            List<string> HSCPgmstau = new List<string>();
            List<string> InclusivectoMu = new List<string>();
            List<string> Monotop = new List<string>();
            List<string> MuMuG = new List<string>();
            List<string> PPD = new List<string>();
            List<string> PhotonIndBkgGGToEE = new List<string>();
            List<string> ST = new List<string>();
            List<string> SingleEta = new List<string>();
            List<string> SingleMuMinusFlatPt3To70 = new List<string>();
            List<string> SingleNeutrino = new List<string>();
            List<string> SingleNeutron = new List<string>();
            List<string> SinglePhoton = new List<string>();
            List<string> THQ = new List<string>();
            List<string> THW = new List<string>();
            List<string> TTToSemiLeptonic = new List<string>();
            List<string> TTWJetsToLNu = new List<string>();
            List<string> TTWJetsToQQ = new List<string>();
            List<string> TTZToLLNuNu = new List<string>();
            List<string> TTZToQQ = new List<string>();
            List<string> TUnpart = new List<string>();
            List<string> VVTo2L2Nu_13TeV = new List<string>();
            List<string> WBJetsToLNu = new List<string>();
            List<string> WGJJToLNu = new List<string>();
            List<string> WLLJJToLNu = new List<string>();
            List<string> WZJJ = new List<string>();
            List<string> WZJToLLLNu = new List<string>();
            List<string> WmWmJJ = new List<string>();
            List<string> WpWpJJ = new List<string>();
            List<string> XXTo4J = new List<string>();
            List<string> ZLLGJets = new List<string>();
            List<string> ZNuNuGJets = new List<string>();
            List<string> ZZJJTo4L = new List<string>();
            List<string> tZq = new List<string>();
            List<string> ttHJetToGG = new List<string>();
            List<string> ttHJetToNonbb = new List<string>();
            List<string> ttHJetToTT = new List<string>();
            List<string> ttHJetTobb = new List<string>();
            List<string> ttWJets = new List<string>();
            List<string> ttbb = new List<string>();

           

            if (File.Exists(textFile))
            {
                using (StreamReader file = new StreamReader(textFile))
                {
                    string All;

                    while ((All = file.ReadLine()) != null)
                    {

                        if (All.Contains("DStarToD0Pi"))
                            DStarToD0Pi.Add(All);
                        else if (All.Contains("DsToTauNeutrinoToMuMuMuNeutrino"))
                            DsToTauNeutrinoToMuMuMuNeutrino.Add(All);
                        else if (All.Contains("EEG"))
                            EEG.Add(All);
                        else if (All.Contains("ExtendedWeakIsospinModel"))
                            ExtendedWeakIsospinModel.Add(All);
                        else if (All.Contains("GluGluSpin0ToGG"))
                            GluGluSpin0ToGG.Add(All);
                        else if (All.Contains("HSCPgmstau"))
                            HSCPgmstau.Add(All);
                        else if (All.Contains("InclusivectoMu"))
                            InclusivectoMu.Add(All);
                        else if (All.Contains("Monotop"))
                            Monotop.Add(All);
                        else if (All.Contains("MuMuG"))
                            MuMuG.Add(All);
                        else if (All.Contains("PPD"))
                            PPD.Add(All);
                        else if (All.Contains("PhotonIndBkgGGToEE"))
                            PhotonIndBkgGGToEE.Add(All);
                        else if (All.Contains("ST"))
                            ST.Add(All);
                        else if (All.Contains("SingleEta"))
                            SingleEta.Add(All);
                        else if (All.Contains("SingleMuMinusFlatPt3To70"))
                            SingleMuMinusFlatPt3To70.Add(All);
                        else if (All.Contains("SingleNeutrino"))
                            SingleNeutrino.Add(All);
                        else if (All.Contains("SingleNeutron"))
                            SingleNeutron.Add(All);
                        else if (All.Contains("SinglePhoton"))
                            SinglePhoton.Add(All);
                        else if (All.Contains("THQ"))
                            THQ.Add(All);
                        else if (All.Contains("THW"))
                            THW.Add(All);
                        else if (All.Contains("TTToSemiLeptonic"))
                            TTToSemiLeptonic.Add(All);
                        else if (All.Contains("TTWJetsToLNu"))
                            TTWJetsToLNu.Add(All);
                        else if (All.Contains("WLLJJToLNu"))
                            WLLJJToLNu.Add(All);
                        else if (All.Contains("TTWJetsToQQ"))
                            TTWJetsToQQ.Add(All);
                        else if (All.Contains("TTZToLLNuNu"))
                            TTZToLLNuNu.Add(All);
                        else if (All.Contains("TTZToQQ"))
                            TTZToQQ.Add(All);
                        else if (All.Contains("TUnpart"))
                            TUnpart.Add(All);
                        else if (All.Contains("VVTo2L2Nu_13TeV"))
                            VVTo2L2Nu_13TeV.Add(All);
                        else if (All.Contains("WBJetsToLNu"))
                            WBJetsToLNu.Add(All);
                        else if (All.Contains("WGJJToLNu"))
                            WGJJToLNu.Add(All);
                        else if (All.Contains("WLLJJToLNu"))
                            WLLJJToLNu.Add(All);
                        else if (All.Contains("WZJJ"))
                            WZJJ.Add(All);
                        else if (All.Contains("WZJToLLLNu"))
                            WZJToLLLNu.Add(All);
                        else if (All.Contains("WmWmJJ"))
                            WmWmJJ.Add(All);
                        else if (All.Contains("WpWpJJ"))
                            WpWpJJ.Add(All);
                        else if (All.Contains("XXTo4J"))
                            XXTo4J.Add(All);
                        else if (All.Contains("ZLLGJets"))
                            ZLLGJets.Add(All);
                        else if (All.Contains("ZNuNuGJets"))
                            ZNuNuGJets.Add(All);
                        else if (All.Contains("ZZJJTo4L"))
                            ZZJJTo4L.Add(All);
                        else if (All.Contains("tZq"))
                            tZq.Add(All);
                        else if (All.Contains("ttHJetToGG"))
                            ttHJetToGG.Add(All);
                        else if (All.Contains("ttHJetToNonbb"))
                            ttHJetToNonbb.Add(All);
                        else if (All.Contains("ttHJetToTT"))
                            ttHJetToTT.Add(All);
                        else if (All.Contains("ttHJetTobb"))
                            ttHJetTobb.Add(All);
                        else if (All.Contains("ttWJets"))
                            ttWJets.Add(All);
                        else if (All.Contains("ttbb"))
                            ttbb.Add(All);

                    }
                    file.Close();
                
                }
            }
            Console.WriteLine("DStarToD0Pi:");
            for (int i = 0; i < DStarToD0Pi.Count; i++)
                Console.WriteLine(DStarToD0Pi[i]);

            Console.WriteLine("\n");

            Console.WriteLine("DsToTauNeutrinoToMuMuMuNeutrino:");
            for (int i = 0; i < DsToTauNeutrinoToMuMuMuNeutrino.Count; i++)
                Console.WriteLine(DsToTauNeutrinoToMuMuMuNeutrino[i]);

            Console.WriteLine("\n");
            Console.WriteLine("EEG:");
            for (int i = 0; i < EEG.Count; i++)
                Console.WriteLine(EEG[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" ExtendedWeakIsospinModel:");
            for (int i = 0; i < ExtendedWeakIsospinModel.Count; i++)
                Console.WriteLine(ExtendedWeakIsospinModel[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" GluGluSpin0ToGG:");
            for (int i = 0; i < GluGluSpin0ToGG.Count; i++)
                Console.WriteLine(GluGluSpin0ToGG[i]);

            Console.WriteLine("\n");
            Console.WriteLine("HSCPgmstau: ");
            for (int i = 0; i < HSCPgmstau.Count; i++)
                Console.WriteLine(HSCPgmstau[i]);

            Console.WriteLine("\n");
            Console.WriteLine("InclusivectoMu:");
            for (int i = 0; i < InclusivectoMu.Count; i++)
                Console.WriteLine(InclusivectoMu[i]);

            Console.WriteLine("\n");
            Console.WriteLine("Monotop:");
            for (int i = 0; i < Monotop.Count; i++)
                Console.WriteLine(Monotop[i]);

            Console.WriteLine("\n");
            Console.WriteLine("MuMuG:");
            for (int i = 0; i < MuMuG.Count; i++)
                Console.WriteLine(MuMuG[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" PPD:");
            for (int i = 0; i < PPD.Count; i++)
                Console.WriteLine(PPD[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" PhotonIndBkgGGToEE:");
            for (int i = 0; i < PhotonIndBkgGGToEE.Count; i++)
                Console.WriteLine(PhotonIndBkgGGToEE[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" ST:");
            for (int i = 0; i < ST.Count; i++)
                Console.WriteLine(ST[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" SingleEta:");
            for (int i = 0; i < SingleEta.Count; i++)
                Console.WriteLine(SingleEta[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" SingleMuMinusFlatPt3To70:");
            for (int i = 0; i < SingleMuMinusFlatPt3To70.Count; i++)
                Console.WriteLine(SingleMuMinusFlatPt3To70[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" SingleNeutrino:");
            for (int i = 0; i < SingleNeutrino.Count; i++)
                Console.WriteLine(SingleNeutrino[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" SingleNeutron:");
            for (int i = 0; i < SingleNeutron.Count; i++)
                Console.WriteLine(SingleNeutron[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" SinglePhoton:");
            for (int i = 0; i < SinglePhoton.Count; i++)
                Console.WriteLine(SinglePhoton[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" THQ:");
            for (int i = 0; i < THQ.Count; i++)
                Console.WriteLine(THQ[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" THW:");
            for (int i = 0; i < THW.Count; i++)
                Console.WriteLine(THW[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" TTToSemiLeptonic:");
            for (int i = 0; i < TTToSemiLeptonic.Count; i++)
                Console.WriteLine(TTToSemiLeptonic[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" TTWJetsToLNu:");
            for (int i = 0; i < TTWJetsToLNu.Count; i++)
                Console.WriteLine(TTWJetsToLNu[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" TTWJetsToQQ:");
            for (int i = 0; i < TTWJetsToQQ.Count; i++)
                Console.WriteLine(TTWJetsToQQ[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" TTZToLLNuNu:");
            for (int i = 0; i < TTZToLLNuNu.Count; i++)
                Console.WriteLine(TTZToLLNuNu[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" TTZToQQ:");
            for (int i = 0; i < TTZToQQ.Count; i++)
                Console.WriteLine(TTZToQQ[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" TUnpart:");
            for (int i = 0; i < TUnpart.Count; i++)
                Console.WriteLine(TUnpart[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" VVTo2L2Nu_13TeV:");
            for (int i = 0; i < VVTo2L2Nu_13TeV.Count; i++)
                Console.WriteLine(VVTo2L2Nu_13TeV[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" WBJetsToLNu:");
            for (int i = 0; i < WBJetsToLNu.Count; i++)
                Console.WriteLine(WBJetsToLNu[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" WGJJToLNu:");
            for (int i = 0; i < WGJJToLNu.Count; i++)
                Console.WriteLine(WGJJToLNu[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" WLLJJToLNu:");
            for (int i = 0; i < WLLJJToLNu.Count; i++)
                Console.WriteLine(WLLJJToLNu[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" WZJJ:");
            for (int i = 0; i < WZJJ.Count; i++)
                Console.WriteLine(WZJJ[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" WZJToLLLNu:");
            for (int i = 0; i < WZJToLLLNu.Count; i++)
                Console.WriteLine(WZJToLLLNu[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" WmWmJJ:");
            for (int i = 0; i < WmWmJJ.Count; i++)
                Console.WriteLine(WmWmJJ[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" WpWpJJ:");
            for (int i = 0; i < WpWpJJ.Count; i++)
                Console.WriteLine(WpWpJJ[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" XXTo4J:");
            for (int i = 0; i < XXTo4J.Count; i++)
                Console.WriteLine(XXTo4J[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" ZLLGJets:");
            for (int i = 0; i < ZLLGJets.Count; i++)
                Console.WriteLine(ZLLGJets[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" ZNuNuGJets:");
            for (int i = 0; i < ZNuNuGJets.Count; i++)
                Console.WriteLine(ZNuNuGJets[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" ZZJJTo4L:");
            for (int i = 0; i < ZZJJTo4L.Count; i++)
                Console.WriteLine(ZZJJTo4L[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" tZq:");
            for (int i = 0; i < tZq.Count; i++)
                Console.WriteLine(tZq[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" ttHJetToGG:");
            for (int i = 0; i < ttHJetToGG.Count; i++)
                Console.WriteLine(ttHJetToGG[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" ttHJetToNonbb:");
            for (int i = 0; i < ttHJetToNonbb.Count; i++)
                Console.WriteLine(ttHJetToNonbb[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" ttHJetToTT:");
            for (int i = 0; i < ttHJetToTT.Count; i++)
                Console.WriteLine(ttHJetToTT[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" ttHJetTobb:");
            for (int i = 0; i < ttHJetTobb.Count; i++)
                Console.WriteLine(ttHJetTobb[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" ttWJets:");
            for (int i = 0; i < ttWJets.Count; i++)
                Console.WriteLine(ttWJets[i]);

            Console.WriteLine("\n");
            Console.WriteLine(" ttbb:");
            for (int i = 0; i < ttbb.Count; i++)
                Console.WriteLine(ttbb[i]);


        }
    }
}
