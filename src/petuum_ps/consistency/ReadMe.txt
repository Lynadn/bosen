ReadMe.txt

:Author: XiaoshuWang
:Email: 2012wxs@gmail.com
:Date: 2018-03-05 19:09

called by petuum_common/ClientTable.*:
consistency:
SSPPushAppendOnlyConsistencyController call SSPPushConsistencyController
SSPPushConsistencyController call SSPConsistencyController
SSPConsistencyController call ptetuum_ps_common/abstract_consistency_controller.hpp

SSPPushConsistencyController call SSPConsistencyController

SSPAggrValueConsistencyController call SSPAggrConsistencyController
SSPAggrConsistencyController call SSPPushConsistencyController


SSPAggrConsistencyController call SSPPushConsistencyController

oplog:

