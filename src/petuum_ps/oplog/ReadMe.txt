ReadMe.txt

:Author: XiaoshuWang
:Email: 2012wxs@gmail.com
:Date: 2018-03-05 19:41

called by petuum_ps/client_table.cpp

dense_oplog* and sparse_oplog* call create_row_oplog*
create_row_oplog* call petuum_ps_common/oplog directly and some call petuum_ps/meta_row_oplog.hpp
