# Prodej použitého zboží

ANetCa umožňuje speciální režim EET pro prodej použitého zboží pro plátce DPH následně. Pro neplátce DPH se tento režim nevztahuje, prodej použitého zboží evidují jako běžnou tržbu bez DPH.

1\) Je zapotřebí mít založeny speciální DPH skupiny pro prodej použitého zboží

* PO-DPH21 kde % DPH bude 21
* PO-DPH15 kde % DPH bude 15
* PO-DPH10 kde % DPH bude 10
* ZPO-DPH21 kde % DPH bude 0
* ZPO-DPH15 kde % DPH bude 0
* ZPO-DPH10 kde % DPH bude 0

2\) Vytvořit položku s PO-DPH21, která bude evidovat marži

3\) Vytvořit položku s ZPO-DPH21, která bude evidovat nákupní cenu zboží.

4\) V modelovém příkladu účtování prodeje zboží za 1500,- Kč, kde nákupní cena činí 1000,- Kč a marže 500,- Kč je zapotřebí namarkovat 1000,- Kč v režimu ZPO-DPH21 a 500,- Kč v režimu PO-DPH21.

