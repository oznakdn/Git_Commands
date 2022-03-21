
<h3>Temel Komutlar</h3>
<table>
    <thead>
        <tr>
          <th>Komut</th>
          <th>Görev</th>
        </tr>
    </thead>
    <tbody>
        <tr>
          <td>git init</td>
          <td>Çalıştırıldığı dosyanın git ile ilk bağlantısını sağlar</td>
        </tr>
        <tr>
          <td>git status</td>
          <td>Stage area'ya alınacak yada commit edilecek dosyaların durumunu gösterir</td>
        </tr>
        <tr>
          <td>git add dosyaAdı</td>
          <td>Belirtilen dosyayı stage'a alır yani commitlemeye hazır hale getirir</td>
        </tr>
        <tr>
          <td>git add .</td>
          <td>Bütün dosyaları stage'a alır yani commitlemeye hazır hale getirir</td>
        </tr>
        <tr>
          <td>git commit -m "commit mesajı"</td>
          <td>Stage alınan dosyaları commit eder</td>
        </tr> 
        <tr>
          <td>git log</td>
          <td>Yapılan commit loglarını gösterir</td>
        </tr>   
    </tbody>
</table>
<h3>Branch ve Stash Komutları</h3>
<table>
    <thead>
        <tr>
          <th>Komut</th>
          <th>Görev</th>
        </tr>
    </thead>
    <tbody>
        <tr>
          <td>git branch</td>
          <td>Branchleri listeler</td>
        </tr> 
        <tr>
           <td>git branch -r</td>
           <td>Remote (uzak/github) branchleri listeler</td>
        </tr>
        <tr>
            <td>git branch brancAdı</td>
            <td>Yeni branch oluşturur</td>
        </tr>
        <tr>
            <td>git switch branchAdı</td>
            <td>Belirtilen branch'e geçiş yapmayı sağlar</td>
        </tr>
     </tbody>
  <table>
     <thead>
        <tr>
            <th>Komut</th>
            <th>Görev</th>
        </tr>
      </thead>
   <tbody>
        <tr>
            <td>git stash </td>
            <td>Başka bir branch'e geçerken henüz commitlemek istemediğimiz çalışmaların silinmemesi için saklar</td>
        </tr> 
        <tr>
            <td>git stash list</td>
            <td>Stash'leri listeler</td>
        </tr>
        <tr>
            <td>git stash clear</td>
            <td>Stash'leri siler</td>
        </tr>
        <tr>
            <td>git stash pop</td>
            <td>Commitlemeye hazır olduğumuz çalışmaları stash'den çıkarark commit'e hazır hale getirir</td>
        </tr>
    </tbody>
  </table>
  
  
  <h3>Merge Komutları</h3>
<table>
    <thead>
        <tr>
          <th>Komut</th>
          <th>Görev</th>
        </tr>
    </thead>
    <tbody>
        <tr>
          <td>git merge branchAdı</td>
          <td>İçinde bulunduğumuzu branch'i komutta belirtilen branch ile birleştirir</td>
        </tr>
    </tbody>
</table>
