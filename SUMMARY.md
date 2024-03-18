# EasyRL4Rec-doc

- [Welcome to EasyRL4Rec!](README.md)
  * [Installation](Introduction/Installation.md)
  * [Running Commands](Introduction/RunningCommands.md)
  * [Implementation Details](Introduction/ImplementationDetails.md)

- [Documentation for src/core](src/Docs.md)

  - [Collector](src/core/collector/README.md)

    - [Collector](src/core/collector/collector.md)
    - [Collector Set](src/core/collector/collector_set.md)

  - [Envs](src/core/envs/README.md)

    - [Coat](src/core/envs/Coat/README.md)
      * [Coat Data](src/core/envs/Coat/CoatData.md)
      * [Coat Env](src/core/envs/Coat/CoatEnv.md)
    - [KuaiRand Pure](src/core/envs/KuaiRand_Pure/README.md)
      * [Kuai Rand Data](src/core/envs/KuaiRand_Pure/KuaiRandData.md)
      * [Kuai Rand Env](src/core/envs/KuaiRand_Pure/KuaiRandEnv.md)
      * [Preprocessing Kuairand](src/core/envs/KuaiRand_Pure/preprocessing_kuairand.md)
    - [KuaiRec](src/core/envs/KuaiRec/README.md)
      * [Kuai Data](src/core/envs/KuaiRec/KuaiData.md)
      * [Kuai Env](src/core/envs/KuaiRec/KuaiEnv.md)
      * [Preprocessing Kuairec](src/core/envs/KuaiRec/preprocessing_kuairec.md)
    - [MovieLens](src/core/envs/MovieLens/README.md)
      * [MovieLens Data](src/core/envs/MovieLens/MovieLensData.md)
      * [MovieLens Env](src/core/envs/MovieLens/MovieLensEnv.md)
    - [SimulatedEnv](src/core/envs/Simulated_Env/README.md)
      * [Base](src/core/envs/Simulated_Env/base.md)
      * [Intrinsic](src/core/envs/Simulated_Env/intrinsic.md)
      * [Penalty Ent Exp](src/core/envs/Simulated_Env/penalty_ent_exp.md)
      * [Penalty Var](src/core/envs/Simulated_Env/penalty_var.md)
    - [YahooR3](src/core/envs/YahooR3/README.md)
      * [Yahoo Data](src/core/envs/YahooR3/YahooData.md)
      * [Yahoo Env](src/core/envs/YahooR3/YahooEnv.md)

    * [Base Data](src/core/envs/BaseData.md)
    * [Base Env](src/core/envs/BaseEnv.md)

  - [Evaluation](src/core/evaluation/README.md)

    * [Evaluator Static](src/core/evaluation/evaluator_static.md)
    * [Evaluator](src/core/evaluation/evaluator.md)
    * [Loggers](src/core/evaluation/loggers.md)
    * [Metrics](src/core/evaluation/metrics.md)
    * [Utils](src/core/evaluation/utils.md)

  - [Policy](src/core/policy/README.md)

    * [RecPolicy](src/core/policy/RecPolicy.md)

  - [State Tracker](src/core/state_tracker/README.md)

    * [Average](src/core/state_tracker/Average.md)
    * [Base](src/core/state_tracker/base.md)
    * [Caser](src/core/state_tracker/Caser.md)
    * [GRU](src/core/state_tracker/GRU.md)
    * [NextItNet](src/core/state_tracker/NextItNet.md)
    * [SASRec](src/core/state_tracker/SASRec.md)

  - [User Model](src/core/userModel/README.md)

    * [User Model Ensemble](src/core/userModel/user_model_ensemble.md)
    * [User Model Mmoe](src/core/userModel/user_model_mmoe.md)
    * [User Model Pairwise Variance](src/core/userModel/user_model_pairwise_variance.md)
    * [User Model Pairwise](src/core/userModel/user_model_pairwise.md)
    * [User Model Variance](src/core/userModel/user_model_variance.md)
    * [User Model](src/core/userModel/user_model.md)

  - [Util](src/core/util/README.md)

    * [Data](src/core/util/data.md)
    * [Inputs](src/core/util/inputs.md)
    * [Layers](src/core/util/layers.md)
    * [Loss](src/core/util/loss.md)
    * [Static Dataset](src/core/util/static_dataset.md)
    * [Utils](src/core/util/utils.md)
