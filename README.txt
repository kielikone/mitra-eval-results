The files contain the machine translations for the test sentences using different configurations of our system.

== Datasets ==

The two datasets used are:

eduskunta       Finnish Parliament
tuli-metsässä   Forest Fires

The test sentences used are presented in eduskunta.{fi,en} and tuli-metsässä.{fi,en}. Respectively, the vocabularies are included in the files eduskunta.tsv and tuli-metsässä.tsv.

For the details of these datasets, please refer to our paper.

== Configurations ==

The configurations are named using the following identifiers:

File Name       Identifier in Paper
(empty)         Mitra-F
bt              Mitra-FB
forest          Mitra-T
forest-bt       Mitra-TB
poro            Poro
mixtral2        Mixtral
noconstraints   Unconstrained

The files containing "mc" contain translations with a maximum number of constraint. These files have been included for completeness's sake, although we had not time to write about this experiment in our paper.

== Human evaluation results ==

The human evaluation results are included in the CSV files.

The Finnish names for the grades are the following:

Käännös OK      Acceptable
Rajoite väärin  Constraints applied wrongly
Käännös huono   Other error
Käännös OK (tunnistus väärin)
                Acceptable even though constraints were not met

== Human evaluation sheets ==

The original human evaluation sheets are included in TSV files.

The files contain the sentences in rows and their different translations in columns.
The order of the columns has been randomized, so the sentences need to be matched with the sentences in the JSONL files to retrieve the system information.

The grades used for the evaluation are:

1 - Acceptable
2 - Constraints applied wrongly
3 - Other error
4 - Acceptable even though constraints were not met


