新增服务商
tc.service.service.create

获取省份
tc.service.service.province
参数:
area_id: 地区id

获取城市
tc.service.service.city
参数:
province_id: 省份id

获取乡镇
tc.service.service.country
参数:
city_id: 城市id

新增服务商提交
tc.service.service.store
参数:
$business = array(
    'name'  =>  '服务商名称',
    'level' =>  '等级',
    'type'  =>  '类型',
    'area' => '1',
    'province' => '6',
    'city' => '83',
    'county' => '765',
    'company_name' => '好极有限公司',
    'uscc' => '统一社会信用代码',
    'legal_name' => '法人名',
    'legal_phone' => '法人电话',
    'legal_email' => '法人email',
    'contact_email' => '联系人email',
    'contact_name' => '联系人名',
    'contact_phone' => '联系人电话',
    'office_address' => '办公地址',
    'note' => '备注',
);


服务商列表页
tc.service.service.index
搜索参数:
开始时间: begin_ctime      end_ctime
修改时间: begin_utime    end_utime
服务商等级: level
服务商类型: type
搜素框: search

导出
tc.service.service.export
搜索参数和index方法一样

编辑页面
tc.service.service.edit
参数: id 

编辑提交:
tc.service.service.update
参数:
'id' => 1,  //多了id
'name'  =>  '服务商名称',
'level' =>  '等级',
'type'  =>  '类型',
'area' => '1',
'province' => '6',
'city' => '83',
'county' => '765',
'company_name' => '好极有限公司',
'uscc' => '统一社会信用代码',
'legal_name' => '法人名',
'legal_phone' => '法人电话',
'legal_email' => '法人email',
'contact_email' => '联系人email',
'contact_name' => '联系人名',
'contact_phone' => '联系人电话',
'office_address' => '办公地址',
'note' => '备注',


服务商列表关联的商家列表
tc.service.service.relationBusiness
参数: 
service_id 服务商id
name 搜索参数:商家名称


















