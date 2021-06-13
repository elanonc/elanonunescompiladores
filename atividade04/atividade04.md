# Atividade 02

## Nome: Elano Nunes Caitano
## Matrícula: 0473434

### Questão 01:
<p>
exp -> exp soma termo					                  <pre>[exp -> exp soma termo] <br />
    -> exp soma termo soma termo			                   [exp -> exp soma termo] <br />
    -> termo soma termo soma termo			                   [exp -> termo] <br />
    -> fator soma termo soma termo			                   [termo -> fator] <br />
    -> numero soma termo soma termo			                   [fator -> numero] <br />
    -> numero + termo soma termo			                   [soma -> +] <br />
    -> numero + termo mult fator soma termo		               [termo -> termo mult fator] <br />
    -> numero + fator mult fator soma termo		               [termo -> fator] <br />
    -> numero + numero mult fator soma termo		           [fator -> numero] <br />
    -> numero + numero * fator soma termo		               [mult -> *] <br />
    -> numero + numero * numero soma termo		               [fator -> numero] <br />
    -> numero + numero * numero – termo			               [soma -> -] <br />
    -> numero + numero * numero – fator			               [termo -> fator] <br />
    -> numero + numero * numero – numero 		               [fator -> numero]
  </p>
