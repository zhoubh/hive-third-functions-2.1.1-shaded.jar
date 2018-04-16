# hive-third-functions-2.1.1-shaded.jar

add jar hdfs://nsha/user/xxx/udf/hive-third-functions-2.1.1-shaded.jar;
CREATE TEMPORARY FUNCTION get_valid_imei AS 'cc.shanruifeng.functions.eId.UDFGetValidImei';
CREATE TEMPORARY FUNCTION get_valid_mac AS 'cc.shanruifeng.functions.eId.UDFGetValidMac';
CREATE TEMPORARY FUNCTION get_valid_mobile AS 'cc.shanruifeng.functions.eId.UDFGetValidMobile';
CREATE TEMPORARY FUNCTION is_valid_id_card AS 'cc.shanruifeng.functions.card.UDFChinaIdCardValid';
CREATE TEMPORARY FUNCTION is_valid_imei AS 'cc.shanruifeng.functions.eId.UDFisValidImei';
CREATE TEMPORARY FUNCTION is_valid_mac AS 'cc.shanruifeng.functions.eId.UDFisValidMac';
CREATE TEMPORARY FUNCTION is_valid_mobile AS 'cc.shanruifeng.functions.eId.UDFisValidMobile';
