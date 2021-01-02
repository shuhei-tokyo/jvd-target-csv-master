# jvd-target-csv-master
JRA-VAN DataLab. Target の開催成績 csv 出力にて使用されている各種コードをまとめる。

- jvd コード: [JRA-VAN Data Lab. SDK](https://jra-van.jp/dlb/sdv/sdk.html) で規定されたコード (v.4.5.1.5)
- target コード： [Target](http://faqnavi13a.csview.jp/faq2/userqa.do?user=jravan&faq=faq01_target&id=285&parent=20) で規定されたコード

## Target 開催成績 csv 出力項目

- 赤マーカ: 対応する jvd コードあり
- 青マーカ: 対応する target コードあり

![target_csv_output_list_master](https://user-images.githubusercontent.com/32590520/103270516-73010e00-49fb-11eb-8412-24107ab13879.png)

## jvd/target コード一覧
target csv 項目名 | 対応 jvd/target コード名 | csv | issue
-- | -- | -- | --
場所 | jvd 競馬場コード | [jvd_course_master.csv](./csv/jvd_course_master.csv) | [issues/5](https://github.com/shuhei-tokyo/jvd-target-csv-master/issues/5)
グレードコード | jvd グレードコード | [jvd_grade_master.csv](./csv/jvd_grade_master.csv) | [issues/6](https://github.com/shuhei-tokyo/jvd-target-csv-master/issues/6)
年齢限定(競走種別コード) | jvd 競走種別コード | [jvd_race_breed_qualification_master.csv](./csv/jvd_race_breed_qualification_master.csv) | [issues/7](https://github.com/shuhei-tokyo/jvd-target-csv-master/issues/7)
競走記号コード | jvd 競走記号コード | [jvd_race_mark_master.csv](./csv/jvd_race_mark_master.csv) | [issues/8](https://github.com/shuhei-tokyo/jvd-target-csv-master/issues/8)
重量コード | jvd 重量種別コード | [jvd_race_weight_regulation_master.csv](./csv/jvd_race_weight_regulation_master.csv) | [issues/9](https://github.com/shuhei-tokyo/jvd-target-csv-master/issues/9)
トラックコード(JV) | jvd トラックコード | [jvd_track_classification_master.csv](./csv/jvd_track_classification_master.csv) | [issues/10](https://github.com/shuhei-tokyo/jvd-target-csv-master/issues/10)
馬場状態 | jvd 馬場状態コード | [jvd_track_condition_master.csv](./csv/jvd_track_condition_master.csv) | [issues/11](https://github.com/shuhei-tokyo/jvd-target-csv-master/issues/11) 
天候 | jvd 天候コード | [jvd_weather_master.csv](./csv/jvd_weather_master.csv) | [issues/12](https://github.com/shuhei-tokyo/jvd-target-csv-master/issues/12)
異常コード | jvd 異常区分コード | [jvd_accident_master.csv](./csv/jvd_accident_master.csv) | [issues/13](https://github.com/shuhei-tokyo/jvd-target-csv-master/issues/13)
性別 | jvd 性別コード | [jvd_gender_master.csv](./csv/jvd_gender_master.csv) | [issues/14](https://github.com/shuhei-tokyo/jvd-target-csv-master/issues/14)
毛色 | jvd 毛色コード | [jvd_coat_color_master.csv](./csv/jvd_coat_color_master.csv) | [issues/15](https://github.com/shuhei-tokyo/jvd-target-csv-master/issues/15)
所属 | jvd 東西所属コード | [jvd_belongings_master.csv](./csv/jvd_belongings_master.csv) | [issues/16](https://github.com/shuhei-tokyo/jvd-target-csv-master/issues/16)
クラスコード | target クラスコード | [target_race_class_master.csv](./csv/target_race_class_master.csv) | [issues/2](https://github.com/shuhei-tokyo/jvd-target-csv-master/issues/2)
トラックコード | target トラックコード | [target_track_type_master.csv](./csv/target_track_type_master.csv) | [issues/3](https://github.com/shuhei-tokyo/jvd-target-csv-master/issues/3)
脚質 | target 脚質 | [target_running_style_master.csv](./csv/target_running_style_master.csv) | [issues/4](https://github.com/shuhei-tokyo/jvd-target-csv-master/issues/4)